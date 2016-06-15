Supervisord
===========

Install and configure supervisord to manage services.

Requirements
------------

None. This role is very basic.

Include this role via galaxy and write custom roles to setup your services in
the `/etc/supervisor/cond.d directory`.

Role Variables
--------------

See `defaults/main.yml`

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: supervisor }

License
-------

MIT

Author Information
------------------

pdeaudney@gmail.com

Pull requests happily merged.

TODO
----

Add optional configuration logic to enable the http or socket server.
Template the entire main configuration.
