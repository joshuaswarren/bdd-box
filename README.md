# bdd-box
Simple Vagrant box based on scotch-io/scotch-box for my BDD talks

Prerequisites
-------------
[Vagrant](http://www.vagrantup.com/downloads.html)
[Virtualbox](https://www.virtualbox.org/wiki/Downloads)

Sample Usage
------------
git clone https://github.com/joshuaswarren/bdd-box
cd bdd-box
cd public
git clone https://github.com/joshuaswarren/bdd
cd .. 
vagrant up
vagrant ssh
cd /var/www/public/bdd/
composer update
Open http://192.168.33.10/bdd/ in your web browser and you should see "Welcome to the world of BDD"

To use Behat or phpspec
cd /var/www/public/bdd/
bin/behat
bin/phpspec run

When you're done:
Exit the VM with 'logout'
Power down the VM with 'vagrant halt'

