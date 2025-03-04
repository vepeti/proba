# How to use
- Edit the hosts.ini, add target hosts or groups
- The playbook runs with root default. If you want to change it, edit the main.yml
- Run ansible-playbook with the following command:
 ```ansible-playbook -e target=<target name from hosts ini> main.yml```
