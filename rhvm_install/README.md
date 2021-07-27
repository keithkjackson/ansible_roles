# rhvm-setup
Playbook for installing a Red Hat Virtualization Manager

This will configure a System or VM to Register to a Satellite, enable the required repositories, install the packages, and perform the engine-setup without any user input.

Currently the playbook can only install an External Manager fully unattended using ansible.  Unattended hosted-engine is in the works to be added at a later time.

To run the playbook, edit the rhvm_answers.conf with the values specific for your deployment and set the variables for the roles to your environment.  
