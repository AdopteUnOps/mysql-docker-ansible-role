# mysql-docker-ansible-role

Ansible role to run a mysql container.
Additionnaly this container can perform mysql optimize on a cron basis and do backup on s3.

Role Variables
--------------

```
mysql_user: "demo"
mysql_password: "demo"
mysql_database: "demo"

mysql_version: 5.7
mysql_root_password: "aeBu2oe2Li"
mysql_host: localhost
mysql_port: 3306

mysql_optimize_cron: "0 0 * * *"

# s3 backup
mysql_backup_enabled: false
mysql_s3_access_key: ""
mysql_s3_secret_key: ""
mysql_s3_bucket: ""
mysql_s3_prefix: ""
mysql_s3_region: ""
mysql_s3_schedule: ""

```
License
-------

Apache License 2
