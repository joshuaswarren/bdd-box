# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "scotch/box"
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.hostname = "bddbox"
  config.vm.synced_folder ".", "/var/www", :mount_options => ["dmode=777", "fmode=777"]

end
