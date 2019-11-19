## Homework -  icinga2

##### You can use any host for check as google.com.ua or www.softserveinc.com

###  Tasks:

* add new host with http check

  * add to host tcp check (ping host)

  

  ##### Additional task 

* add to host dns check A record (check examples from demo)

___

Software requirements:

- Vagrant
- VirtualBox

___

#### How to setup icinga2 virtual machine

Clone icinga2-vagrant git repo

``` git clone https://github.com/Icinga/icinga-vagrant.git```

Run virtual machine with icinga

```bash
cd standalone
vagrant up
```

Connect to vm via ssh

```bash
vagrant ssh
```

___

### Usefull commands

Check icinga2 configuration 

```bash
icinga2 daemon -C
```

Reload icinga2

```bash
systemctl reload icinga2.service
```

Destoy vagrant vm

```bash
vagrant destroy
```

Demo configs: `/etc/icinga2/demo`

____

## Overview icinga2web

Navigate to http://192.168.33.5

Login: icingaadmin

Password: icingaadmin

______





