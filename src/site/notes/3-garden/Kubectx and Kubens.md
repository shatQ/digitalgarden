---
{"dg-publish":true,"permalink":"/3-garden/kubectx-and-kubens/","tags":["note","seedling","public"],"created":"2023-09-22 14:33","updated":"2024-11-28T21:22"}
---

[[2-topics/k8s\|k8s]]
# Kubectx and Kubens

## Kubectx

With this tool, you don’t have to make use of lengthy “kubectl config” commands to switch between contexts. This tool is particularly useful to switch context between clusters in a multi-cluster environment. Installation:

```
$ git clone https://github.com/ahmetb/kubectx /opt/kubectx  
$ ln -s /opt/kubectx/kubectx /usr/local/bin/kubectx
```

## Kubens

This tool allows users to switch between namespaces quickly with a simple command. Installation:

```
$ git clone https://github.com/ahmetb/kubectx /opt/kubectx  
$ ln -s /opt/kubectx/kubens /usr/local/bin/kubens
```

---
