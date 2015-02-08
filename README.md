# cloud-config
My cloud config model for CoreOs with great attention at iptables configuration.

A discovery service, https://discovery.etcd.io, is provided as a free service to help connect etcd instances together by storing a list of peer addresses and metadata under a unique address, known as the discovery URL. You can generate them very easily:

$ curl -w "\n" https://discovery.etcd.io/new


