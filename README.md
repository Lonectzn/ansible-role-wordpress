Wordpress
=========

Installs Wordpress using the wp-cli

Requirements
------------

It is expected that apache and a mysql compatible database are installed.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

No dependencies

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lonectzn.wordpress, wp.db.name: wp, wp.db.user: wordpress, wp.db.pass: xxxx }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
