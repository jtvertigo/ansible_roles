# Collection of useful ansible roles

## os_base_setup
Base OS components setup (Ubuntu 20.04, Ubuntu 22.04)
## node_exporter
Install node_exporter (Ubuntu 20.04, Ubuntu 22.04)
## postgresql_1c
Setup PostgreSQL cluster (build from 1C) on Ubuntu 20.04, Ubuntu 22.04, should use ```os_base_setup``` role before
## keepalived
Setup keepalived (for using with haproxy + Patroni) for high availability (Ubuntu 20.04, Ubuntu 22.04)
## haproxy
Setup haproxy (for using with keepalived + Patroni) for high availability (Ubuntu 20.04, Ubuntu 22.04)
## k8s
Setup kubernetes cluster (control-plane node) with kubeadm on Ubuntu 22.04
