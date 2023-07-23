# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  # The most common configuration options are documented and commented below.
  # For a complete reference, please see the online documentation at
  # https://docs.vagrantup.com.

  # Specify the Vagrant box you want to use. Replace "base" with the desired box name.
  config.vm.box = "ubuntu/bionic64"

  # Configure the amount of memory (RAM) for the virtual machine.
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "4096"  # 4GB RAM
	vb.gui = true
  end

  # Share a folder from the host machine to the guest VM.
  config.vm.synced_folder "C:/Users/path/to/your/file", "/vagrant_share", create: true

  # Disable automatic box update checking. If you disable this, then
  # boxes will only be checked for updates when the user runs
  # `vagrant box outdated`. This is not recommended.
  # config.vm.box_check_update = false

  # Additional configurations for your VM can be added here.
end
