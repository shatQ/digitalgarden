---
{"dg-publish":true,"permalink":"/1-mocs/kubernetes-moc/","tags":["moc"],"created":"2024-11-28T10:21","updated":"2024-11-28T21:17"}
---

# Kubernetes MOC

## Architecture

- [[3-notes/Etcd\|Etcd]] - It is a strongly consistent, distributed key-value store that stores information about the cluster.
- [[3-notes/Kube-scheduler\|Kube-scheduler]] - Responsible for scheduling application containers on worker nodes
- [[3-notes/Kube-controller-manager\|Kube-controller-manager]] - Take care of different cluster functions, e.g. node controller, replication controller, etc.
- [[3-notes/Kube-apiserver\|Kube-apiserver]] - Responsible for orchestrating all operations within the cluster.
- [[3-notes/Kubelet\|Kubelet]] - Listens for instructions from kube-apiserver and manages containers.
- [[3-notes/Kube-proxy\|Kube-proxy]] - Helps enabling communication between services within the cluster.
- [[3-notes/Container Runtimes\|Container Runtimes]]
- [[3-notes/Kubernetes API\|Kubernetes API]]
- [[3-notes/Static Pods\|Static Pods]]
- [[3-notes/Init Containers\|Init Containers]]
## Security

- [[3-notes/RBAC\|RBAC]]
- [[3-notes/ServiceAccounts\|ServiceAccounts]]
## Network

- [[3-notes/DNS\|DNS]]
- [[3-notes/Ingress\|Ingress]]
- [[3-notes/Network Policies\|Network Policies]]
- [[3-notes/Services\|Services]]
## Scheduling

- [[3-notes/Node Affinity\|Node Affinity]]
- [[3-notes/Node Selector\|Node Selector]]
- [[3-notes/Node Name\|Node Name]]
- [[3-notes/Taints and Tolerations\|Taints and Tolerations]]
## Maintenance

- [[3-notes/Cluster Upgrades\|Cluster Upgrades]]
- [[3-notes/Backup and Restore\|Backup and Restore]]
## Tools

- [[3-notes/kubectl-cheatsheet\|kubectl-cheatsheet]]
- [[3-notes/Kubectx and Kubens\|Kubectx and Kubens]]
- [[3-notes/Kubectl Convert Plugin\|Kubectl Convert Plugin]]
## Other

-  [[3-notes/CKAD Simulator Kubernetes 1.26\|CKAD Simulator Kubernetes 1.26]]