Ansible Role: fabos.k8s.setup
=========

The role provides task files for installing and uninstalling k8s on target hosts as well as scaling the number of k8s workers.

Requirements
------------

The role is only tested for specific Linux Distributions/Versions (see meta/main.yml).

Role Variables
--------------

No parameters required.

Dependencies
------------

None.

Example Playbook
----------------

See playbook files in root folder:

- install.yml
- uninstall.yml
- scaleup.yml
- scaledown.yml

License
-------

MIT

Author Information
------------------

Lukas Rauh - Fraunhofer IPA