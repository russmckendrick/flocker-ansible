Flocker Ansible
====================

This playbook builds out an AWS environment, launches x number of Ubuntu 16.04 instances and installs and configures both a Flocker and Docker Swarm cluster;

```
ansible-playbook -i hosts site.yml --extra-vars "aws_access_id=You_IAM_Access_Key" --extra-vars "aws_secret_key=Your_IAM_Secret_Key"
```

There are some variables you can tweak in the `group_vars/environment.yml` file, but you should be able to leave everything as is.
