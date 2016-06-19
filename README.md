Ansible libbitcoin role
=======================

Installs a libbitcoin server using Debian packages. Supported distributions are Debian Jessie (8.0) and Ubuntu Xenial (16.04).

First create your hosts file like:

    [servers]
    SERVER_IP ansible_ssh_user=root ansible_ssh_port=22

Remember to replace SERVER\_IP, ssh user and ssh port if necessary.

Then run the playbook:

    ansible-playbook -i hosts init.yml

Vagrant
=======

You can also run it using vagrant:

    vagrant up

It will automatically redirect the query and heartbeat ports in the guest machine to 19091 and 19092 in the host machine.

Author
======

- Pablo Castellano
