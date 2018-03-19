# WildFlyAnsible


## This PlayBook install Wildfly in domain Mode.

The host inventory is an example for play the book, modify the hostname of master and slave node that you need to install.

Inside the group_vars change the variable value as desired

Supported Opereting system Centos 7.x 64 bit


This is the list ov variables inside group_vars valid for all host
-----
ACCOUNT: admin
PASSWORD: test
master_node: masternode
syncuser: syncuser ###User for remote node
syncpassword: test ###Password for syncuser
-----
