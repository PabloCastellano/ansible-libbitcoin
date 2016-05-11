Ansible libbitcoin role
=======================

Installs a libbitcoin server using Debian packages.

First create your hosts file like:

    [servers]
    SERVER_IP ansible_ssh_user=root ansible_ssh_port=22

Remember to replace SERVER\_IP, ssh user and ssh port if necessary.

Then run the playbook:

    ansible-playbook -i hosts init.yml

Author
======

- Pablo Castellano
