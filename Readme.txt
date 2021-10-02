##Before it begins install harbor make sure :
##1.you have internet connection    ##dhclient
##if you change youre server name and yyou have a self-signed ssl create a new one and beware to set your new fqdn in ssl
##2.selinux is disabled ## sestatus or cat /etc/selinux/config
##3.base repo is enabled /etc/yum.repos.d/Centos-Base.repos
##4.dns is set ## /etc/resolv.conf nameserver 4.2.2.4

##your firewall may cause your connection
##copy daemon.json in all clients (/etc/docker/daeon.json)then you must reset your daemon and docker
##you must login to harbor ##docker login harbor_Server_domain
##you must create apublic project to store your images