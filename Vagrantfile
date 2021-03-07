# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANT_NAME = "eval_laravel450"
VAGRANT_IP = "192.168.33.45"

Vagrant.configure('2') do |config|
       config.vm.box = 'ubuntu/xenial64'
       config.vm.network 'private_network', ip: VAGRANT_IP
       config.vm.synced_folder './data', '/var/www/html'
       config.vm.provider 'virtualbox' do |vb|
			#vb.gui = true
			vb.memory = "2048"
			vb.name = VAGRANT_NAME
       end
   end
