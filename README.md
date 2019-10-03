# vagrant-apache-php5-mysql

## Description

Vagrant box ubuntu/trusty64

## Included Applications

* Apache 2
* PHP 5.6
* MySQL
* PhpMyAdmin
* Composer
* Git
* ADT

## Vagrant

Vagrant file: 
    
    Vagrantfile

Vagrant config file: 

    bootstrap.sh
   
Destroy vagrant box

   vagrant destroy 
   
Run vagrant box

    vagrant up    
    
If you ever change your "bootstrap.sh" file, you'll need to run command

    vagrant reload --provision
    
Access the box

    vagrant ssh
    
### Access web server from host browser

You need to go to http://192.168.50.11/ADT in the browser.

### Access phpMyAdmin from host browser

You need to go to http://192.168.50.11/phpmyadmin in the browser. Credentials: root:root.