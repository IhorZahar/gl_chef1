# Tasks:
- generate blank cookbook
- add Vagrantfile
- create and up blank vagrant machine
- install mysql server manually.
- set root user password.
- create database, user.
- destroy machine.
- implement all mysql install steps with chef code
- save DB user/name in attributes.

# Advanced Tasks:
- Make cookbook idempotent.
- Populate DB schema with some sample schema of your choice ( store schema in cookbook_files)
- Tune innodb_buffer_size parameter with my.cnf config ( use template resource)
- configure root mysql client with root access password ( my.cnf setting)
