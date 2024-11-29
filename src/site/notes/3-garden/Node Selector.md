---
{"dg-publish":true,"permalink":"/3-garden/node-selector/","tags":["note","seedling","public"],"created":"2023-02-07","updated":"2024-11-28T21:27"}
---

[[2-topics/k8s\|k8s]]
# Node Selector

`nodeSelector` is the simplest recommended form of node selection constraint. You can add the `nodeSelector` field to your Pod specification and specify the [node labels](https://kubernetes.io/docs/concepts/scheduling-eviction/assign-pod-node/#built-in-node-labels) you want the target node to have. Kubernetes only schedules the Pod onto nodes that have each of the labels you specify.

## Labeling a Node

```console
kubectl label nodes node1 tier=dev
```

```console
kubectl get nodes --show-labels

NAME           STATUS   ROLES           AGE   VERSION   LABELS
node1          Ready    control-plane   40m   v1.26.0   ...,kubernetes.io/hostname=node1,tier=dev
```

## Adding Node Selector to a Pod

```yaml
apiVersion: v1
kind: Pod
metadata:
  name: nginx
  labels:
    env: test
spec:
  nodeSelector:
    tier: dev
  containers:
  - name: nginx
    image: nginx
```

---
- https://kubernetes.io/docs/concepts/scheduling-eviction/assign-pod-node/
