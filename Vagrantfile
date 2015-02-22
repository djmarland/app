# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "scotch/box"
  config.vm.network "private_network", ip: "192.168.33.11"
  config.vm.hostname = "scotchbox"
  config.vm.synced_folder ".", "/var/www", :mount_options => ["dmode=777", "fmode=666"]

end


# To setup:
# Install PHP 5.6
# Install Nginx
# Setup Nginx to point at the application (HTTPS?)
# Setup the hostname
# Install and run composer
# Install and run grunt
# Install MySQL
# Install phpMyAdmin
# Setup database
# Run migrations
# Setup elasticsearch/logstash