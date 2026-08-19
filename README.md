# Ansible Role for Updating OpenSSH
**Author/Maintainer:** Josh Murphy

An extremely basic role to update openssh on RedHat and Debian to avoid outdated openssh versions.

Requirements
------------

N/A

Role Variables
--------------

rl_update_only - Whether to update only on RedHat, or to install the missing openssh packages. Leave true if you don't want openssh-client installed.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

```yaml
- hosts: all
  become: yes

  roles:
    - role: openssh-update
```

License
-------

MIT

### From Ansible Galaxy

```bash
ansible-galaxy install crowjm64.openssh_update
```

This role was created and is maintained by **[CrowJM64](https://github.com/CrowJM64)**.
