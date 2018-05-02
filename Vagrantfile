# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "geerlingguy/centos7"
  config.vm.network "forwarded_port", guest: 3142, host:2202 
  config.vm.network "private_network", ip: "192.168.50.51"
  config.vm.provider "virtualbox" do |vb|
     vb.memory = "2048"
  end
end
