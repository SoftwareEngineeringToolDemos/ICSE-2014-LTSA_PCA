Details on vm built using Vagrant
------

Environment
------
__Virtual Box used:__ [box-cutter/ubuntu1404-desktop](https://atlas.hashicorp.com/box-cutter/boxes/ubuntu1404-desktop)

Folder content
-----
This build-vm folder contains following things:
- __README.md file__
- __Vagrantfile__
  This is the script (& configuration) file of the VM.


Steps to create a VM using this build
-----

1. Download [Vagrant](https://www.vagrantup.com/)
2. Install Vagrant
3. Download [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
4. Install VirtualBox
5. Download all files from [build-vm](https://github.com/SoftwareEngineeringToolDemos/ICSE-2014-LTSA_PCA/new/master/build-vm) to local machine.
6. Open a command line/teminal window and go to build-vm folder
7. Run "__vagrant up__"
8. Please wait until "__vagrant up__" finishes execution before working on GUI.

***

* This install Oracle JAVA 8. 
* Also copies the LTSA-PCA jar file and examples to the Desktop.

***

Reference
-----
1. http://askubuntu.com/questions/56104/how-can-i-install-sun-oracles-proprietary-java-jdk-6-7-8-or-jre
2. https://github.com/pussinboots/vagrant-devel/blob/master/provision/packages/java8.sh
3. https://docs.vagrantup.com/v2/getting-started/
