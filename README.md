# mysql-replication

this is tool helper to create mysql replication master-slave

requirement :
- python-minimal
- python-pip
- python-mysqldb


## example playbook
```
- hosts: mysql
  become: yes
  vars_files:
   - config.yml
  roles:
   - mysql-replication
```

for example config.yml you can copy from default main.yml
