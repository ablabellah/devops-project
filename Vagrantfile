# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  
  #Will not check for box updates during every startup.
 config.vm.box_check_update = false


 # Master node where ansible will be installed
 config.vm.define "ansible" do |ansible|
   ansible.vm.box = "hashicorp/bionic64"
   ansible.vm.hostname = "ansible"
   ansible.vm.network "private_network", ip: "192.168.10.10"
   ansible.vm.provider "virtualbox" do |vb|
    
   end
 end


 config.vm.define "prod" do |prod|
   prod.vm.box = "hashicorp/bionic64"
   prod.vm.hostname = "prod"
   prod.vm.network "private_network", ip: "192.168.10.20"
   prod.vm.provider "virtualbox" do |vb|
     
   end
 end


 config.vm.define "test" do |test|
   test.vm.box = "hashicorp/bionic64"
   test.vm.hostname = "test"
   test.vm.network "private_network", ip: "192.168.10.30"
   test.vm.provider "virtualbox" do |vb|
     
   end
 end

 config.vm.define "registre" do |registre|
   registre.vm.box = "hashicorp/bionic64"
   registre.vm.hostname = "registre"
   registre.vm.network "private_network", ip: "192.168.10.40"
   registre.vm.provider "virtualbox" do |vb|
     
   end
 end

end



  
