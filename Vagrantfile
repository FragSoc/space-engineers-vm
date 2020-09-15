# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "gusztavvargadr/windows-server"

  config.vm.network "forwarded_port", guest: 27016, host: 27016

  config.vm.synced_folder "./saves", "C:\\SpaceEngineersData"

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "8192"
  end

  config.vm.provision "ansible" do |a|
    a.playbook = "./playbook.yml"
  end
end
