# redis64

### Ubuntu-16 with Redis installed on it.
----------------------------------------------------------------------------------------------------------------
### Requirements
- The following software must be installed on your local machine before you can use Packer to build the Vagrant box file:

- [Packer](http://www.packer.io/)
- [Vagrant](http://vagrantup.com/)
- [VirtualBox](https://www.virtualbox.org/)
----------------------------------------------------------------------------------------------------------------------------

### This repository contains template for Ububtu-16 with Redis that can create Vagrant base box using Packer.

### Packer command
- `packer build template.json`

- This command creates the box for Vagrant.
------------------------------------------------------------------------------------------------------------------------
### Vagrant command
- vagrant box add "packer box name here"

- This add's the box created from the packer command into Vagrant's local store.

- `vagrant up`

Will start the VM box.
