# ansible-vagrant-GAVS

<b>Pre-Requisites:</b> </br>
1. Install Vagrant from this <a href="https://www.vagrantup.com/downloads.html ">link</a> </br>
2. Install VirtualBox from this <a href="https://www.virtualbox.org/wiki/Linux_Downloads">link</a> </br>  
3. Install Ansible by using these commands </br>

    sudo apt-get update
    sudo apt-get install software-properties-common

Once the package is installed, we can add the Ansible PPA by typing the following command:

    sudo apt-add-repository ppa:ansible/ansible

Press ENTER to accept the PPA addition.

Next, we need to refresh our system's package index so that it is aware of the packages available in the PPA. Afterwards, we can install the software:

    sudo apt-get update
    sudo apt-get install ansible
    

<b>Provisioning: </b> </br>
Once you are done installing the prerequisites, copy all files to the project Root folder.
Then run this command

    $ vagrant up

Upon, success, , verify your LAMP server by opening this link on your browser: http://localhost:8080/info.php

-- <i><b>Dibin Dixit M </b></i>
