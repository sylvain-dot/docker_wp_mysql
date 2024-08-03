# -*- mode: ruby -*-
# vi: set ft=ruby :

RAM = 1024
IPx = "192.168.29.6"
CPU = 2

Vagrant.configure("2") do |config|
  config.vm.box = "alvistack/ubuntu-22.04"
  config.vm.network "private_network", ip: IPx
  config.vm.hostname = "ubuntu"

  config.vm.provider "virtualbox" do |v|
    v.memory = RAM
    v.cpus = CPU
  end

end
