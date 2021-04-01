# cml-ansible 

This respository contains several playbooks to configure or backup Cisco IOS and NXOS devices. 
The devices are running in CML (Cisco Modeling Labs).

## Setup

Ansible was installed on Ubuntu 20.04.2 LTS server

```
jbowman@utils:~/cml-ansible$ ansible --version
ansible 2.9.6
  config file = /home/jbowman/cml-ansible/ansible.cfg
  configured module search path = ['/home/jbowman/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/lib/python3/dist-packages/ansible
  executable location = /usr/bin/ansible
  python version = 3.8.5 (default, Jan 27 2021, 15:41:15) [GCC 9.3.0]
jbowman@utils:~/cml-ansible$
```

## Tested Platforms

Tested using Cisco Modeling Labs:
  * IOS Router ---> IOSv 15.8(3)
  * IOS Switch ---> IOSv L2 2019
  * NXOS Switch ---> NXOS 9.2.3

## Toplogy

!(https://github.com/zephyr2095/cml-ansible/images/CML-Ansible-diagram.jpg)