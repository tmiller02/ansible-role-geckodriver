Ansible Role: Geckodriver
=========================

Installs [geckodriver](https://github.com/mozilla/geckodriver) on RHEL/CentOS and Ubuntu/Debian.

Role Variables
--------------

Available role variables are listed below, along with default values:

    geckodriver_version: "0.26.0"
    
The version of geckodriver to download and install.

    geckodriver_prefix: "/usr/local/bin"
    
The prefix to install geckodriver under.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
        - tmiller02.geckodriver

License
-------

MIT

