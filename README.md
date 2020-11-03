docker
=========

Ansible role that will install Docker


Role Variables
--------------

The only variable you should set is
```
docker_users:
  - user1
  - user2
```

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: frite.docker, docker_users: ["user1", "user2"] }

License
-------

MIT
