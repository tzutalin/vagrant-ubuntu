# -*- mode: ruby -*-
# vi: set ft=ruby :

NODE_IP = "192.168.50.4"
NODE_MEMORY_SIZE = 2048
NODE_VCPUS = 2

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/xenial64"

  config.vm.network :private_network, ip: NODE_IP

  config.vm.provider :virtualbox do |vb|
     vb.memory = NODE_MEMORY_SIZE
     vb.cpus = NODE_VCPUS
  end


end
