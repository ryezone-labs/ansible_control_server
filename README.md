ryezone_labs.ansible_control_server
=========

This role applies configuration settings unique to the ansible control server.

Requirements
------------

- ssh-keygen

Role Variables
--------------

### Global Variables

- `ryezone_labs_provision_user` (string)

  This value sets the owner of the ssh keys for the provisioning user.

### Role Variables

- `ansible_provision_user` (string)

  This value sets the owner of the ssh keys for the provisioning user.  Defaults to `ryezone_labs_provision_user`.

License
-------

BSD
