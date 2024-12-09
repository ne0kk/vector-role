Vector Role
=========
роль для установки Vector


Requirements
------------

centos7

Role Variables
--------------

vector.yaml.j2
/etc/vector/vector.yaml

Dependencies
------------

NOt

Example Playbook
----------------

vector:
  hosts:
    vector-01:
      ansible_host: 62.84.124.102
      ansible_private_key_file: ~/.ssh/id_rsa
      ansible_ssh_user: centos


License
-------

BSD

Author Information
------------------

github.com/ne0kk/vector-role
