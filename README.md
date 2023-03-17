## pi-setup

This playbook will perform the following tasks:

Update and upgrade the Raspberry Pi's apt packages.
Install Git.
Install Python3 and pip.
Install Flask using pip3.

## To Run

1. Ensure that you have installed and updated ansible on your control machine. 
2. Check that you can ssh into the pi. Make sure that you replace the variables in the inventory.ini file.
3. Run the playbook with: ansible-playbook -i inventory.ini raspberry_pi_setup.yml
