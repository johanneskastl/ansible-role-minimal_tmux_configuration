![Ansible Lint](https://github.com/johanneskastl/ansible-role-minimal_tmux_configuration/workflows/Ansible%20Lint/badge.svg)

minimal_tmux_configuration
=========

Create a minimal tmux configuration file (`.tmux.conf`).

Requirements
------------

None.

Role Variables
--------------

- `additional_users`: (optional) Other users except the root user, that should
  get a `~/.tmux.conf`. A good idea would be to create one for the
  `ansible_user`...
- `tmuxconf_for_root`: (optional) Boolean that decides if this role should
  create a `.tmux.conf` for the root user (default is `true`)


Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: 'johanneskastl.minimal_tmux_configuration'
          additional_users:
            - jane.doe

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via git@johannes-kastl.de.
