## ABOUT

Ansible modules for Cisco Nexus 9000.  Developed for Ansible 1.5.  This library is not currently part of the Ansible distribution.  Please refer to [INSTALLATION](#installation) section for setup.

## OVERVIEW OF MODULES

Work in progress, please see [library](library) directory for modules.  The modules are documented per-Ansible guidelines; look for the DOCSTRING within each file.

## INSTALLATION

This repo assumes you have the DEPENDENCIES installed on your system.  You can then `git clone` this repo and run the `env-setup` script in the repo directory:

    user@ansible-nxapi> source env-setup
    
This will set your `$ANSIBLE_LIBRARY` variable to the repo location and the installed Ansible library path.  For example:

````
[mierdin@ansible-nxapi]$ echo $ANSIBLE_LIBRARY
/home/mierdin/Ansible/ansible-nxapi/library:/usr/share/ansible
````
Alternatively you can copy the files in the [library](library) directory into the ansible installed directory: library/net_infrastructure


## DEPENDENCIES


Thes modules require the following to be installed on the Ansible server:

* [Ansible](http://www.ansible.com) 1.5 or later
* Matt's fork of [nexus9000](https://github.com/mierdin/nexus9000) (be sure to build)



