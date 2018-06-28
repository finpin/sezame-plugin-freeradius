# sezame freeradius plugin

## on centos/redhat based systems

yum -y install policycoreutils-python

semanage  fcontext -a -t radiusd_exec_t sezame-freeradius/bin/auth
