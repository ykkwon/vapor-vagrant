# Vapor Vagrant Box
This is everything you ned to start developing and test a vapor project on ubuntu 14.04 - Trusty Tahr
## Requirements
### VirtualBox
https://www.virtualbox.org/wiki/Downloads
### Vagrant
https://www.vagrantup.com/
### Supported Platforms
* Mac OS X
* Windows
* Linux (Debian & Centos)


## Getting started

### Cloning and building the box
```sh
git clone https://github.com/paulatwilson/vapor-vagrant <project-directory>
cd <project-directory>
vagrant up
```

### Building and running project

#### In the vagrant VM
```sh
vagrant ssh
cd /vagrant/www
vapor build
vapor run
```
#### On host machine
Simply open your favourite browser and go to: http://192.168.33.10

## Access the source of your project
You can now access the source code for your project by looking in: 
```sh
<project-directory>/www 
```

You can edit it in your favourite editor, recommendations are:
* Xcode (Mac only)
* Atom 
 * Download: https://atom.io/
 * Article on getting atom working with swift: https://medium.com/@Aciid/hacking-atom-to-create-a-swift-ide-that-runs-on-linux-and-mac-c7d9520a0fac#.nhnmu8ylc
* Sublime Text
 * Download: http://www.sublimetext.com/ 


