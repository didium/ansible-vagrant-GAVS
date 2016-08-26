# ansible-vagrant-GAVS

Pre-Requisites:
1. Install Vagrant from this <a href="https://www.vagrantup.com/downloads.html ">link</a>
2. Install VirtualBox from this <a href="https://www.virtualbox.org/wiki/Linux_Downloads">link</a>  
3. Install Ansible by using these commands

    sudo apt-get update
    sudo apt-get install software-properties-common

Once the package is installed, we can add the Ansible PPA by typing the following command:

    sudo apt-add-repository ppa:ansible/ansible

Press ENTER to accept the PPA addition.

Next, we need to refresh our system's package index so that it is aware of the packages available in the PPA. Afterwards, we can install the software:

    sudo apt-get update
    sudo apt-get install ansible
    

Steps:
Once you are done installing the prerequisites, copy all files to the project Root folder.
Then run this command

    $ vagrant up

Upon, success, , verify your LAMP server by opening this link on your browser: http://localhost:8080/info.php

-- Dibin Dixit M, Didium Technologies
