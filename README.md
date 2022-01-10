# Instalacja
- eval `ssh-agent`
- ssh-add id_student
- ssh ec2-user@<ip_maszyny> -i id_student 
(To both machines to verify)
- ansible-playbook -i hosts.ini setup.yaml

## App

![app](chrome_slElIAhXWn.png)

## Network

User -> Proxy -> Internet -> Load Balancer -> Nodes -> Web Server