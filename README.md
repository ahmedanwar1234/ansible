# ansible
# fucker


sudo firewall-cmd --ad-port=80/tcp
    ----> this command for enable to access the ip at port 80

ansible-playbook --list-tags site.yml 
   --> this command list of tags in site.yml

ansible-playbook --tags apache --ask-become-pass site.yml 
     --> this command run olny tasks have tag apache 

 sudo firewall-cmd --add-port=80/tcp
                 -->  permission to enable ip in port 80/tcp

