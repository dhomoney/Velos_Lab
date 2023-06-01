# Velos Lab

This is an ansible playbook fully configure 3 Ubuntu 22.04 servers. This includes:
- Running updates
- Adding users
- Adding docker repos
- Installing docker and docker-compose
- Setting up Juice Shop container on port 3000
- Setting up crAPI container on port 5000
- Pulling down vAPI container

Future Goals are to automatically deploay the Ubuntu Servers, do base config to get them on the network, and then fully configure. This is helping me to better learn Ansible. Feel free to fork and use whatever you want. 

05/09/23 - UPDATE

Created playbook to automatically update the ubuntu servers and reboot them if there has been a kernel update. 

06/01/23 - UPDATE

Laudato Cor Sacratissimum!

Much has been update. The initial build has added in the Hackazon docker container to add additional testing options. Also created a playbook to install Traceable.ai's TPA on Ubuntu 22.04 and an client jump host build out. 