---
{"dg-publish":true,"permalink":"/1-mocs/kubernetes-moc/","tags":["moc"],"created":"2024-11-28T10:21","updated":"2024-11-28T11:20"}
---

# Kubernetes MOC

## Architecture

- [[kubernetesOLD/Etcd\|Etcd]] - It is a strongly consistent, distributed key-value store that stores information about the cluster.
- [[kubernetesOLD/Kube-scheduler\|Kube-scheduler]] - Responsible for scheduling application containers on worker nodes
- [[kubernetesOLD/Kube-controller-manager\|Kube-controller-manager]] - Take care of different cluster functions, e.g. node controller, replication controller, etc.
- [[kubernetesOLD/Kube-apiserver\|Kube-apiserver]] - Responsible for orchestrating all operations within the cluster.
- [[kubernetesOLD/Kubelet\|Kubelet]] - Listens for instructions from kube-apiserver and manages containers.
- [[kubernetesOLD/Kube-proxy\|Kube-proxy]] - Helps enabling communication between services within the cluster.
- [[kubernetesOLD/Container Runtimes\|Container Runtimes]]
- [[kubernetesOLD/Kubernetes API\|Kubernetes API]]
- [[kubernetesOLD/Static Pods\|Static Pods]]
- [[kubernetesOLD/Init Containers\|Init Containers]]
## Security

- [[kubernetesOLD/RBAC\|RBAC]]
- [[kubernetesOLD/ServiceAccounts\|ServiceAccounts]]
## Network

- [[kubernetesOLD/DNS\|DNS]]
- [[kubernetesOLD/Ingress\|Ingress]]
- [[kubernetesOLD/Network Policies\|Network Policies]]
- [[kubernetesOLD/Services\|Services]]
## Scheduling

- [[kubernetesOLD/Node Affinity\|Node Affinity]]
- [[kubernetesOLD/Node Selector\|Node Selector]]
- [[kubernetesOLD/Node Name\|Node Name]]
- [[kubernetesOLD/Taints and Tolerations\|Taints and Tolerations]]
## Maintenance

- [[kubernetesOLD/Cluster Upgrades\|Cluster Upgrades]]
- [[3-garden/Backup and Restore\|Backup and Restore]]
## Tools

- [[kubernetesOLD/kubectl-cheatsheet\|kubectl-cheatsheet]]
- [[kubernetesOLD/Kubectx and Kubens\|Kubectx and Kubens]]
- [[kubernetesOLD/Install kubectl Convert Plugin\|Install kubectl Convert Plugin]]
## Other

-  [[kubernetesOLD/CKAD Simulator Kubernetes 1.26\|CKAD Simulator Kubernetes 1.26]]