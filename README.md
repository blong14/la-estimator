# la-estimator

## Pre-reqs
- Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- Install [Vagrant](https://www.vagrantup.com/downloads.html)

## Local Development Setup
- Install composer dependencies: `composer install`
- Install homestead: `php vendor/bin/homestead make`
- Currently, the app is located at `/estimator` so you will need to update the `sites` config in Homestead.yaml to point to `/home/vagrant/Code/estimator/public`
- Add line to `/etc/hosts`: `<ip_address> estimator.app` (IP address can be found in Homestead.yml)
- Run the application `vagrant up`

## Developing in Vagrant
- SSH into the vagrant box: `vagrant ssh`
- Navigate to code directory: `cd Code`
