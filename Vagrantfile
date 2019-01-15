# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
    config.vm.box = "subutai/stretch"
    config.vm.provision "ansible", type: "ansible", playbook: "site.yml", verbose: "-vv"
  end
  