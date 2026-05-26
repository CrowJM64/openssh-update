Ansible Role for Updating OpenSSH
=========

An extremely basic role to update openssh on RedHat and Debian to avoid outdated openssh versions.

Requirements
------------

N/A

Role Variables
--------------

# rl_update_only - Whether to update only, or to install the missing openssh packages. Leave true if you don't want openssh-client installed.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts: all
  become: yes

  roles:
    - role: openssh-update

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
