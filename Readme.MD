** ANSIBLE **

* Create 2 AWS ec2-instances, name them as Ansible-Master and Ansible-Node
* Login to Ansible-Master and install ansible running command `sudo dnf install ansible -y` 
* After installing, try running the ping command to check the connection from Master to Node
    `ansible -i <private-ip-of-node-server> -e ansible_user=ec2-user -e ansible_password=<If you setup anypassword; enter password> -m ping