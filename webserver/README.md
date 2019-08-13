webserver
=========

This role will install apache2 server on any ubuntu machine

Requirements
------------

Install Ansible in system.
```
apt-get-install  ansible -y
```
Create role directory
```
mkdir /etc/ansible/roles
cd /etc/ansible/roles
```

Clone role in above repository
To verify the role run following command
```
ansible-galaxy list
```


Role Variables
--------------

A variable "apache2_var" is defined in vars/main.yml.
 

Example Playbook
----------------

Including an example of how to use your role

    - hosts: localhost   //remove localhost and write ip of client node 
      roles:
         - webserver   //write rolename

```
ansible-playbook filename.yml
```

Author Information
------------------
Contact : 9024040756
Email: ankur.mangal24@gmail.com
