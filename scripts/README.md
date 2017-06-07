# TPI-KVM-ZFS-DRP
## prerequisites
* ZFS
* qemu-kvm
## Definitions of script
### replicationZFS
This script work in crontab. This is the main script that is in the crontab of the server. 
### failoverNow  
This script is useful in case I want to switch manually from one host to another
### delOldSnap  
This script is useful in case I want to force to delete the old snapshot
### shutdownKVM  
This script is useful in case I would turn off all vm in one go
### startKVM
This script is useful in case I want to start all vm in one go
