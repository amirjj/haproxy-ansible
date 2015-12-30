Haproxy
===========

HAProxy is free, open source software that provides a high availability load balancer and proxy server for TCP and HTTP-based applications that spreads requests across multiple servers.
This repository is responsible for installation of Haproxy with Ansible configuration management service. It also copies your customized config file exists in "files" folder


Contents
========

**haproxy.yml** :      This is an installation script that with running it, Haproxy will be installed and config files will be copied.

**files/haproxy.cfg**:       This is Haproxy config file that you can replace it with your customized config file.


Prerequisites
=============

* Debian Wheazy
* Ansible 2
* sshpass : apt-get install sshpass


Usage
=====


**1**- chmod a+x haproxy.yml

**2**- Edit hosts file to add your hosts

**3**- Run haproxy.yml with this command:   "ansible-playbook haproxy.yml -vvvv"


Authors
=======

**Author**: Amir Jamshidi jam

**Email**: amir.jamshidijam@gmail.com