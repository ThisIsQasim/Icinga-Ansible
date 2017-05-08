# Icinga-Ansible
Automated Icinga deployment using Ansible on CentOS 7.
Clone this repo, define hosts in <code>icinga.yml</code> and run the following

    ansible-playbook icinga.yml
    
Open the server IP in a browser and run the setup. The token is displayed in terminal during setup. Database user is <code>icinga</code> password is <code>icingapass1</code>. Use <code>icingadb0</code> for user info and <code>icingadb</code> for IDO.
