Memcached
=========

Simple install of memcached

Requirements
------------

None

Dependencies
------------

You'll need dustinrue.xenial-bootstrap

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      become: yes
      gather_facts: no

      roles:
        - dustinrue.xenial-bootstrap
    - hosts: <host>
      become: yes
      gather_facts: yes

      roles:  
         - dustinrue.memcached

License
-------

MIT

