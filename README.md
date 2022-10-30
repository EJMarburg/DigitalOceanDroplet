# DigitalOceanDroplet

This is a simple script that will allow you to create a droplet within DigitalOcean while saving the IP in your hosts file for later use. 

To get started you will need to first create a token, or have a token, from your DigitalOcean account. PLace it in the droplet.yml where it says <Your Digital Ocean Token>. 

In the inventory.yml file under the webservers it says DigitalOceanTest, this is what your droplet will be called. You can change it your domain or any name you would like. Note the more names you have, the more droplets it will create For example: webservers: hosts: DigitalOceanTest: DigitalOceanTest2: and so on. Also in the inventory you will see some variables, these will be needed in the for the SSH key to allow you to remote into the droplet within the same script.
