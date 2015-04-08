Virtual Environment
===================

RDO-Manager can be deployed in a virtual environment using virtual
machines instead of actual baremetal. One baremetal machine is still needed to
act as the host for the virtual machines.


Minimum System Requirements
---------------------------
In order to deploy minimal RDO cloud with RDO-Manager you need 3 virtual machines each consisting of 4GB of memory and 40GB of disk space [#]_.

* 1x Undercloud VM (where RDO-Manager lives)
* 1x Overcloud Controller
* 1x Overcloud Compute

The minimum system requirements for the virtual host machine are then:

* A baremetal machine with virtualization hardware extenstions enabled (ested KVM is not supported).
* 1 quad core CPU
* 12GB free memory
* 120GB disk space

For minimal **HA (high availability)** deployment you need at least 3x Overcloud Controllers which increases the minimum system requirements up to:

* 20GB free memory
* 200GB disk space.


.. _virtual_env:

Preparing Virtual Environment - Automated
-----------------------------------------
To create such an environment you can use instack-undercloud which contains necessary tooling.

Follow `Instack's Virtual Environment Setup <https://repos.fedorapeople.org/repos/openstack-m/instack-undercloud/html/virt-setup.html>`_ documentation.


Preparing Virtual Environment - Manual
--------------------------------------
TBD



.. rubric:: Footnotes

.. [#] The virtual machine disk files are thinly provisioned and will not take up the full space initially.

