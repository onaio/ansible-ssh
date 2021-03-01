onaio - SSH
=========

Performs the following tasks related to SSH in a host:

1. Installs public SSH keys authorized to access the host.
1. Installs SSH CA certificates from Hashicorp Vault authorized to access the host.
1. Hardens the SSHD service (through [dev-sec.ssh-hardening](https://github.com/dev-sec/ansible-ssh-hardening)) by applying recommended secure configurations.

Dependencies
------------

- [dev-sec.ssh-hardening](https://github.com/dev-sec/ansible-ssh-hardening)

License
-------

Apache 2
