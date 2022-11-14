# Cloud Infrastructure Ansible

This github repository is about our Cloud Infrastructure project.

## Prerequisites
 - Create SSH key
 - Install ansible :  `pip install ansible`
 - Install gantsign.visual-studio-code role `ansible-galaxy install gantsign.visual-studio-code `
 - Create 3 VM on the same network with an access to the Internet and a root access.
 - Share the SSH key to the root user.
 
 ## Installation 
 `git clone  git@github.com:dilvy-anais/cloud-infra.git `
  
Then, change the IP address on inventory.yaml. 

## Launch
`cd cloud-infra
 ansible-playbook -i inventory.yaml playbook.yaml
 `
 
