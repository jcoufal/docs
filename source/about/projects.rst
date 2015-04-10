.. _projects:

Individual Projects
===================

.. contents::


Example Category
----------------

Example Project
^^^^^^^^^^^^^^^
This is short description what the project is about and how RDO-Manager uses this project. Three sentences max.

**How to contribute**

* Instructions to prepare development environment. Should be mostly pointing to upstream docs. If upstream docs doesn't exist, please, create one.
  Add tips how to test the feature in RDO-Manager + other useful information.


**Useful links**

* Upstream Project:  `link <#>`_
* Bugs: `link <#>`_
* Blueprints:  `link <#>`_



Installer
---------

instack
^^^^^^^

instack-undercloud
^^^^^^^^^^^^^^^^^^

tripleo-incubator
^^^^^^^^^^^^^^^^^


Shared Libraries
----------------

diskimage-builder
^^^^^^^^^^^^^^^^^

dib-utils
^^^^^^^^^

os-\*-config
^^^^^^^^^^^^

tripleo-image-elements
^^^^^^^^^^^^^^^^^^^^^^


Node Management
---------------

ironic
^^^^^^

Ironic project is responsible for provisioning and managing bare metal
instances.

**How to contribute**

Ironic uses tox_ to manage the development environment, see `upstream
documentation
<http://docs.openstack.org/developer/ironic/dev/contributing.html>`_,
`developer guidelines
<https://wiki.openstack.org/wiki/Ironic/Developer_guidelines>`_
and `OpenStack developer's guide`_ for details.

**Useful links**

* Upstream Project: http://docs.openstack.org/developer/ironic/index.html
* Bugs: https://bugs.launchpad.net/ironic
* Blueprints: https://blueprints.launchpad.net/ironic

  .. note::
    `Specs process <https://wiki.openstack.org/wiki/Ironic/Specs_Process>`_
    should be followed for suggesting new features.

* Approved Specs: http://specs.openstack.org/openstack/ironic-specs/

ironic-discoverd
^^^^^^^^^^^^^^^^

ironic-discoverd project is responsible for discovery of hardware properties
for newly enrolled nodes (see also ironic_). Ironic uses drivers to hide
hardware details behind a common API.

For testing purposes Ironic can also be used for provisioning and managing
virtual machines which act as bare metal nodes via special driver ``pxe_ssh``.

**How to contribute**

ironic-discoverd uses tox_ to manage the development environment, see `upstream
documentation
<https://github.com/stackforge/ironic-discoverd/blob/master/CONTRIBUTING.rst>`_
for details.

**Useful links**

* Upstream Project: https://github.com/stackforge/ironic-discoverd
* PyPI: https://pypi.python.org/pypi/ironic-discoverd
* Bugs: https://bugs.launchpad.net/ironic-discoverd
* Blueprints: https://blueprints.launchpad.net/ironic-discoverd

Networking
----------

neutron
^^^^^^^

?
^


Deployment Planning
-------------------

tuskar
^^^^^^

python-tuskarclient
^^^^^^^^^^^^^^^^^^^


User Interfaces
---------------

tuskar-ui
^^^^^^^^^

tuskar-ui-extras
^^^^^^^^^^^^^^^^

python-rdomanager-oscplugin
^^^^^^^^^^^^^^^^^^^^^^^^^^^


Deployment & Orchestration
--------------------------
heat
^^^^

heat-templates
^^^^^^^^^^^^^^

tripleo-heat-templates
^^^^^^^^^^^^^^^^^^^^^^

puppet-\*
^^^^^^^^^

tripleo-puppet-elements
^^^^^^^^^^^^^^^^^^^^^^^


.. _tox: https://testrun.org/tox/latest/
.. _OpenStack developer's guide: http://docs.openstack.org/infra/manual/developers.html
