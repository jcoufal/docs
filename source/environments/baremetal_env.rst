Baremetal Environment
=====================

RDO-Manager can be deployed in all baremetal environment. One machine will be used for RDO-Manager, the others will be used for your cloud deployment.


Minimum System Requirements
---------------------------
In order to deploy minimal RDO cloud with RDO-Manager you need 3 baremetal machines.

* 1x Undercloud VM (where RDO-Manager lives)
* 1x Overcloud Controller
* 1x Overcloud Compute

There are four Overcloud Roles available so if you want to use all of them, you need at least 5 machines available.

For minimal **HA (high availability)** deployment you need at least 3x Overcloud Controllers which increases the minimum number of machines.

The setup requires baremetal machines with the following minimum specifications:

* multi-core CPU
* 4GB memory
* 60GB free disk space

RDO-Manager (undercloud) is supported only on:

* RHEL 7.1 x86_64 or
* CentOS 7 x86_64


Preparing Baremetal Environment
-------------------------------
Follow `Instack's Baremetal Environment Setup <https://repos.fedorapeople.org/repos/openstack-m/instack-undercloud/html/baremetal-setup.html#preparing-the-baremetal-environment>`_ documentation.
