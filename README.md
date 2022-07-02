thinkpace.ansible_docker
=========

This is a very simple role to install docker.

Dependencies
------------

This role is tested on Ubuntu 20.04 (Focal Fossa).

Example Playbook
----------------

Make sure to install this role is installed before using:

`ansible-galaxy install thinkpace.ansible_docker`

You can update this role with the `--force` flag:

`ansible-galaxy install --force thinkpace.ansible_docker`

This role can be used like following:

```
    - hosts: servers
      roles:
         - { role: thinkpace.ansible_docker }
```

License
-------

GNU Affero General Public License v3.0

Author Information
------------------

[Tobias Baus](https://tobiasbaus.de)
