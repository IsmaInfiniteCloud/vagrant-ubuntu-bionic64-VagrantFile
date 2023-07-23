# Vagrant Configuration for Ubuntu Bionic64 VM

This repository contains a Vagrantfile to set up an Ubuntu Bionic64 virtual machine with 4GB of RAM.

Vagrant Configuration for Ubuntu Bionic64 VM
This repository provides a Vagrantfile to provision an Ubuntu Bionic64 virtual machine with 4GB of RAM. Once set up, you can start and manage your VM with ease.

Prerequisites
VirtualBox: A free and open-source hypervisor for x86 computers.
Vagrant: An open-source software product for building and maintaining portable virtual software development environments.
Ensure both VirtualBox and Vagrant are installed on your host machine before proceeding.

Getting Started
Here's how to get your Ubuntu Bionic64 VM up and running:

Clone the Repository: Clone this repository to your local machine using:

////////////////////////////
git clone [REPO_LINK]
////////////////////////////

Navigate to the Directory: Open a terminal and navigate to the directory containing the cloned repository.

////////////////////////////
cd [DIRECTORY_PATH]
///////////////////////////

Start the VM: Use the command below to provision and start your virtual machine:

////////////////////////////
vagrant up
////////////////////////////

SSH into the VM: Once the VM is up and running, you can access its shell by using:

////////////////////////////
vagrant ssh
////////////////////////////

Shutting Down the VM: When done, you can halt the VM with the following command:

////////////////////////////
vagrant halt
////////////////////////////

Configuration Details
Vagrant Box: ubuntu/bionic64
Memory: 4GB RAM
GUI Enabled: Yes
Folder Sharing
Your local folder at C:/Users/Ismail/Desktop/DevOps/VM/shareFolder is synced with the virtual machine. Inside the VM, you can access its contents at /vagrant_share.

License
This project is distributed under the MIT License. Always refer to the LICENSE file for the latest licensing details.

