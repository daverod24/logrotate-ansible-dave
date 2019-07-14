# logrotate-ansible-dave


```bash
ansible-playbook -i inventory site.yml -vvv

#### crear el archivo inventory
[local]
127.0.0.1 ansible_connection=local ansible_user=david ansible_sudo_password="becomepass"

[server1]
apache2 ansible_connection=ssh ansible_user=devops ansible_sudo_password="becomepass"
```