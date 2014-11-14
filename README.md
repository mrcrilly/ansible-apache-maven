Role Name
=========

Installs the latest Apache Marven binary. Requires Java, but installs it via geerlingguy.java (which is a role dependency)

Requirements
------------

None.

Role Variables
--------------

- mrcrilly_marven_manage_software (default: true)
- mrcrilly_marven_java_version (default: 1.7.0)
- mrcrilly_marven_version (default: 3.2.3)

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: mrcrilly.marven }

License
-------

BSD

Author Information
------------------

- Michael Crilly
- http://mcrilly.me/
- @mrmcrilly
