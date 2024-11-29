---
{"dg-publish":true,"permalink":"/3-garden/kubelet/","tags":["note","seedling","public"],"created":"2023-04-13","updated":"2024-11-28T21:22"}
---

[[2-topics/k8s\|k8s]]
# Kubelet

Kubelet is running on each worker node and tho the following tasks:
- Registers a node within kubernetes cluster
- Create pods on kube-apiserver request
- Monitors node and pods status and reports it to kube-apiserver

Kublet must be always installed and run as systemd service with a config file `/etc/systemd/system/kube-scheduler.service`. 

---

