# cloudstack_kvm_host_installation_automation
This Ansible script will help you to automate the KVM host installation and will ready your KVM host to be added in Cloudstack
This scipt is created for KVM ( CentOS7).
This ansible script will help you to install and configuration of KVM node. This script includes everything which is required 
to add a KVM node as a host. This sccipt is completely modifiable. 
 - Steps for running this script
 - Install Ansible
 - create inventory file and fill the required details 
 - In this script, I am using 4 physical NIC, 2 NIC's are being used for Management BOND and other 2 NIC's are being used for Public bond. My primary storage is directly accessebile through the management network. You can also include 2 Seperate NIC for storage connectivty as well.
- Run the Script and you wil get ready made node. Just go to the cloud and add the nodes.

