# haproxyctl-ansible

Plabooks for installing haproxyctl and enabling/disabling server/service

##Playbook command Usage###

openstack-ansible haproxyctl.yml -e "SERVER=" -e "ACTION="  
openstack-ansible haproxyctl.yml -t list_service  

Example:  
openstack-ansible haproxyctl.yml -e "SERVER="container name (full/wildcard)"" -e "ACTION=enable"  
openstack-ansible haproxyctl.yml -e "SERVER="controller name"" -e "ACTION=enable"  
