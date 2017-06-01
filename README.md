# haproxyctl-ansible

Plabooks for installing haproxyctl and enabling/disabling server/service

##Playbook command Usage###

openstack-ansible haproxyctl.yml -e "SERVER=" -e "ACTION="  
openstack-ansible haproxyctl.yml -t list_service  

Example:  
openstack-ansible haproxyctl.yml -e "SERVER=sdc-openstack-49_rabbit_mq_container" -e "ACTION=enable"  
openstack-ansible haproxyctl.yml -e "SERVER=sdc-openstack-49" -e "ACTION=enable"  
