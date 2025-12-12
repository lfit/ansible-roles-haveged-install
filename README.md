haveged-install
===============

Installs haveged to help systems with low entropy.

**Note:** CentOS Stream 9 and RHEL 9+ are not supported as the haveged package is not available in their repositories. Modern systems typically have sufficient entropy sources.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: lfit.haveged-install }

License
-------

MIT

Author Information
------------------

Linux Foundation Release Engineering
