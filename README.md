# ubuntu-vm-vagrant

*vagrantfile

Vagrant.configure("2") do |config|
  config.vm.box = "gusztavvargadr/windows-10"
end


*Download vagrant box:

vagrant box add bento/ubuntu-16.04
vagrant box add ubuntu/focal64

*List all vagrant boxs

vagrant box list

*Setup Vagrantfile for an image

vagrant init ubuntu/focal64

*Start vagrant box:

vagrant up

*Check status of the box:

vagrant status

*Package your VM:

vagrant package

*Install scp package:

vagrant plugin install vagrant-scp

*ssh into vagrant box:

vagrant ssh

*Shutdown system:

vagrant halt

*Save the current state on VM:

vagrant suspend

*Resume suspended machine:

vagrant resume

*Restart vagrant box:

vagrant reload

*Destroy vagrant box:

vagrant destroy -f
