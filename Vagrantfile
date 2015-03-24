# -*- mode: ruby -*-

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.define :node do |node|
    node.vm.hostname = "node"
    node.vm.network :private_network, ip: "192.168.33.10"
  end

  config.vm.define :LB do |node|
    node.vm.hostname = "LB"
    node.vm.network :private_network, ip: "192.168.33.11"
  end

  config.vm.define :blue do |node|
    node.vm.hostname = "blue"
    node.vm.network :private_network, ip: "192.168.33.12"
  end

  config.vm.define :green do |node|
    node.vm.hostname = "green"
    node.vm.network :private_network, ip: "192.168.33.13"
  end
end
