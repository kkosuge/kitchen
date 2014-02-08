# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure('2') do |config|
  config.vm.box      = 'ubuntu-precise'
  config.vm.box_url  = 'https://cloud-images.ubuntu.com/vagrant/precise/current/precise-server-cloudimg-amd64-vagrant-disk1.box'
  config.vm.network :forwarded_port, guest: 80, host: 5678
end
