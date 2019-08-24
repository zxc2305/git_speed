yum -y install bind-utils
nslookup github.global.ssl.fastly.net
nslookup github.com

vi /etc/hosts
66.220.155.14 global-ssl.fastly.net
13.250.177.223 github.com


sudo /etc/init.d/network restart


