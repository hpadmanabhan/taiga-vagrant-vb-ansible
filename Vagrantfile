# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"

  # Create a private network, which allows host-only access to the machine
  # using a specific IP.
  config.vm.network "private_network", ip: "172.27.33.10"

  config.vm.provider "virtualbox" do |vb|
    vb.name = "taiga_dev"
    vb.cpus = 2
    vb.memory = "1024"
  end
end
