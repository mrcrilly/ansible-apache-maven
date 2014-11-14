# mrcrilly.maven

Installs the latest Apache Maven binary. Requires Java, but installs it via geerlingguy.java (which is a role dependency)

Requirements
------------

None.

Role Variables
--------------

- mrcrilly_maven_manage_software (default: true)
- mrcrilly_maven_java_version (default: 1.7.0)
- mrcrilly_maven_version (default: 3.2.3)

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: mrcrilly.maven }

License
-------

BSD

Author Information
------------------

- Michael Crilly
- http://mcrilly.me/
- @mrmcrilly
