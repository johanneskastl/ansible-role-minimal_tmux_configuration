![Ansible Lint](https://github.com/johanneskastl/ansible-role-minimal_tmux_configuration/workflows/Ansible%20Lint/badge.svg)

minimal_tmux_configuration
=========

Create a minimal tmux configuration file (`.tmux.conf`).

Requirements
------------

None.

Role Variables
--------------

None.

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

I am Johannes Kastl, reachable via kastl@b1-systems.de.
