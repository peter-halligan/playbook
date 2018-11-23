# playbook
## Playbook for initialising minimal ubuntu vps and deploying a static page with nginx
running the playbook `ansible-playbook deploywebsite.yml -i hosts -e "minimal_install=true||false`  
if it is the first run after os reload set minimal_install=true else set it to false  
### this playbook will
* add devops users
* add devops group
* add ssh keys for users
* allow passwordless sudo
* add common packages
* install nginx
* configure nginx
* remove remote root login
* remove password login
