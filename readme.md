## FEBS-Cloud-K8S
FEBS Cloud kubernetes deployment guide,base on kubernetes 1.16.2 cluster.

Steps:

1. Create nfs server.
2. Create nacos cluster.
3. Deploy FEBS server cluster.

Centos virtual machine configuration created with vagrant:

System | IP | Role| CPU cores | RAM| Hostname
---|---|---|---|---|---
CentOS 7| 192.168.33.11| Master| 2 | 2048M |master
CentOS 7| 192.168.33.12| Node1| 2 | 5120M |node1
CentOS 7| 192.168.33.13| Node2| 2 | 5120M |node2
CentOS 7| 192.168.33.14| Node3| 2 | 5120M |node3
CentOS 7| 192.168.33.15| NFS| 1 | 1024M |nfs
CentOS 7| 192.168.33.16| Extend| 2 | 8192M |extend

Diagram:

![Diagram](images/diagram.png)