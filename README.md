osx-ruby
========

An Ansible role to setup ruby on OS X

Requirements
------------

[Homebrew](http://brew.sh/) must be installed.

Role Variables
--------------

osx_ruby_global_gems:
  - bundler
  - compass

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - hnakamur.osx-ruby

License
-------

MIT

Author Information
------------------

[Hiroaki Nakamura]( http://hnakamur.github.io/ )
