# deployment_ansible
playbooks for automated deployment of frontend backend database and identity (docker) of mikha

contains a ready to deploy ansible playbook
requres tweaking of few files like ansible.cfg for user, ssh key, inventory 
for now sudo user is a pre-requisite 

command to execute for deployment: ansible-playbook role_main.yaml
