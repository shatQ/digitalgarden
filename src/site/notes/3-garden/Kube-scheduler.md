---
{"dg-publish":true,"permalink":"/3-garden/kube-scheduler/","tags":["note","seedling","public"],"created":"2023-04-13","updated":"2024-11-28T21:18"}
---

[[2-topics/k8s\|k8s]]
# Kube-scheduler

The kube-scheduler decides on witch node the pod should be running. 

Kube-scheduler can be:
- run as systemd service with a config file `/etc/systemd/system/kube-scheduler.service`
- run as a kubeadmin controled pod with a config file `/etc/kubernetes/manifest/kube-scheduler.yaml` 

---
