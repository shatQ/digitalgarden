---
{"dg-publish":true,"permalink":"/01-mo-cs/kubernetes-moc/","tags":["moc"],"created":"2024-11-28T10:21","updated":"2024-11-28T21:17"}
---

# Kubernetes MOC

## Architecture

- [[03 Notes/Etcd\|Etcd]] - It is a strongly consistent, distributed key-value store that stores information about the cluster.
- [[03 Notes/Kube-scheduler\|Kube-scheduler]] - Responsible for scheduling application containers on worker nodes
- [[03 Notes/Kube-controller-manager\|Kube-controller-manager]] - Take care of different cluster functions, e.g. node controller, replication controller, etc.
- [[03 Notes/Kube-apiserver\|Kube-apiserver]] - Responsible for orchestrating all operations within the cluster.
- [[03 Notes/Kubelet\|Kubelet]] - Listens for instructions from kube-apiserver and manages containers.
- [[03 Notes/Kube-proxy\|Kube-proxy]] - Helps enabling communication between services within the cluster.
- [[03 Notes/Container Runtimes\|Container Runtimes]]
- [[03 Notes/Kubernetes API\|Kubernetes API]]
- [[03 Notes/Static Pods\|Static Pods]]
- [[03 Notes/Init Containers\|Init Containers]]
## Security

- [[03 Notes/RBAC\|RBAC]]
- [[03 Notes/ServiceAccounts\|ServiceAccounts]]
## Network

- [[03 Notes/DNS\|DNS]]
- [[03 Notes/Ingress\|Ingress]]
- [[03 Notes/Network Policies\|Network Policies]]
- [[03 Notes/Services\|Services]]
## Scheduling

- [[03 Notes/Node Affinity\|Node Affinity]]
- [[03 Notes/Node Selector\|Node Selector]]
- [[03 Notes/Node Name\|Node Name]]
- [[03 Notes/Taints and Tolerations\|Taints and Tolerations]]
## Maintenance

- [[03 Notes/Cluster Upgrades\|Cluster Upgrades]]
- [[03 Notes/Backup and Restore\|Backup and Restore]]
## Tools

- [[03 Notes/kubectl-cheatsheet\|kubectl-cheatsheet]]
- [[03 Notes/Kubectx and Kubens\|Kubectx and Kubens]]
- [[03 Notes/Kubectl Convert Plugin\|Kubectl Convert Plugin]]
## Other

-  [[03 Notes/CKAD Simulator Kubernetes 1.26\|CKAD Simulator Kubernetes 1.26]]