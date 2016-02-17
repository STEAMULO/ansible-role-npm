NPM
===

Installation d'un serveur npm
Testé sur un Ubuntu

Requirements
------------

Role Variables
--------------

- Packages npm à installer
    npm_packages:
        - {name: pkg1, version: 1.2.3}
        - {name: pkg2, version: 1.2.3}

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars:
        - npm_packages:
            - {name: gulp, version: 3.8.11}
      roles:
         - { role: steamroles/npm }

License
-------


Author Information
------------------

STEAMULO - http://www.steamulo.com