1. Clone the repository
2. Edit inventory file
   [webservers]
   jenkins-s1

3. #ansible-playbook -i inventory.ini site.yml --extra-vars "ansible_ssh_user=root ansible_ssh_pass=vagrant"

Note: Static Site web content is @ https://github.com/getsaarthak/example-static-site.git
