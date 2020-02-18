# WildFlyAnsible


## This PlayBook install Wildfly in domain Mode.

The host inventory is an example for play the book, modify the hostname of master and slave node that you need to install.

Inside the group_vars change the variable value as desired

Supported Opereting system Centos 7.x 64 bit


This is the list ov variables inside group_vars valid for all host

ACCOUNT: admin <br>
PASSWORD: test <br>
master_node: masternode <br>
syncuser: syncuser ###User for remote node <br>
syncpassword: test ###Password for syncuser <br>


N.B. Per cambiare versione di Wildfly impostare il nome del pacchetto da scaricare nelle group_vars

