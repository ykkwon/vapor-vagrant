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

### Cloning the repo
```sh
git clone https://github.com/paulatwilson/vapor-vagrant <project-directory>
cd <project-directory>
vagrant up
```

### Building and running project

```sh
vagrant ssh
cd /vagrant/www
vapor build
vapor run
```
