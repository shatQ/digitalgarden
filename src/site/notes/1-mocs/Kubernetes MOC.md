---
{"dg-publish":true,"permalink":"/1-mocs/kubernetes-moc/","tags":["moc"],"created":"2024-11-28T10:21","updated":"2024-11-28T21:17"}
---

# Kubernetes MOC

## Architecture

- [[3-garden/Etcd\|Etcd]] - It is a strongly consistent, distributed key-value store that stores information about the cluster.
- [[3-garden/Kube-scheduler\|Kube-scheduler]] - Responsible for scheduling application containers on worker nodes
- [[3-garden/Kube-controller-manager\|Kube-controller-manager]] - Take care of different cluster functions, e.g. node controller, replication controller, etc.
- [[3-garden/Kube-apiserver\|Kube-apiserver]] - Responsible for orchestrating all operations within the cluster.
- [[3-garden/Kubelet\|Kubelet]] - Listens for instructions from kube-apiserver and manages containers.
- [[3-garden/Kube-proxy\|Kube-proxy]] - Helps enabling communication between services within the cluster.
- [[3-garden/Container Runtimes\|Container Runtimes]]
- [[3-garden/Kubernetes API\|Kubernetes API]]
- [[3-garden/Static Pods\|Static Pods]]
- [[3-garden/Init Containers\|Init Containers]]
## Security

- [[3-garden/RBAC\|RBAC]]
- [[3-garden/ServiceAccounts\|ServiceAccounts]]
## Network

- [[3-garden/DNS\|DNS]]
- [[3-garden/Ingress\|Ingress]]
- [[3-garden/Network Policies\|Network Policies]]
- [[3-garden/Services\|Services]]
## Scheduling

- [[3-garden/Node Affinity\|Node Affinity]]
- [[3-garden/Node Selector\|Node Selector]]
- [[3-garden/Node Name\|Node Name]]
- [[3-garden/Taints and Tolerations\|Taints and Tolerations]]
## Maintenance

- [[3-garden/Cluster Upgrades\|Cluster Upgrades]]
- [[3-garden/Backup and Restore\|Backup and Restore]]
## Tools

- [[3-garden/kubectl-cheatsheet\|kubectl-cheatsheet]]
- [[3-garden/Kubectx and Kubens\|Kubectx and Kubens]]
- [[3-garden/Kubectl Convert Plugin\|Kubectl Convert Plugin]]
## Other

-  [[3-garden/CKAD Simulator Kubernetes 1.26\|CKAD Simulator Kubernetes 1.26]]