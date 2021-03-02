onaio - SSH
=========

Performs the following tasks related to SSH in a host:

1. Installs public SSH keys authorized to access the host.
1. Installs SSH CA certificates from Hashicorp Vault authorized to access the host.
1. Hardens the SSHD service (through devsec.hardening.ssh_hardening) by applying recommended secure configurations.

Dependencies
------------

- devsec.hardening.ssh_hardening provided by the [devsec.hardening](https://galaxy.ansible.com/devsec/hardening) collection.

License
-------

Apache 2
