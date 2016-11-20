Flocker Ansible
====================

This assume you have three Ubuntu 16.04 hosts in AWS which are accessibly by the host you are going to be running this playbook on;

```
ansible-playbook -i hosts site.yml --extra-vars "aws_access_id=You_IAM_Access_Key" --extra-vars "aws_secret_key=Your_IAM_Secret_Key"
```

There are some variables you can tweak in the `group_vars/environment.yml` file, but you should be able to leave everything as is.
