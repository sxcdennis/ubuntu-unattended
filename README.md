# ubuntu-unattended

To start creating an unattended ISO. You must first

1. Download create-unattended-iso.sh
1. Change create-unattended-iso.sh permissions to be executable 
1. Download a copy of the iso you need into the root directory (example download ubuntu16.04-server)
1. Change the name of the iso to version that is defined in varible on create-unattended-iso.sh lines 10-13 Example: `ubuntu-16.04-server-amd64.iso` 
1. Edit unattended-ubuntu.seed as needed
1. Run the create-unattended-iso.sh
1. Upload newly created iso to any place wanted to share. 
1. Use iso for unattended installs.
