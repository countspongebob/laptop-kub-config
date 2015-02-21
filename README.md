# laptop-kub-config
Files needed to configure coreos and kubernetes for Mac laptop running coreos VMs.

Needed on master:
apiserver.service
controller-manager.service

Needed on minion nodes:
kublet.service
proxy.service
scheduler.service

Configuration is targeting 
1x master node running etcd, apiserver, and controller-manager
3x minion nodes running kublet, proxy, and scheduler, NOT part of the etcd service

