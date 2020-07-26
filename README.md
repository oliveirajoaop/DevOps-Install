DevOps-Install
==============

This role will install all the necessary software to an Ubuntu DevOps machine to work with Visual Studio Code.

Requirements
------------

A running Ubunto with ssh active and running, you keys added to authorized_keys, access to sudo without password.

Type visudo and change as below

    ...
    # Members of the admin group may gain root privileges
    %admin ALL=(ALL) ALL

    # Allow members of group sudo to execute any command
    %sudo   ALL=(ALL:ALL) NOPASSWD:ALL

    # See sudoers(5) for more information on "#include" directives:
    ...




Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

João Oliveira
