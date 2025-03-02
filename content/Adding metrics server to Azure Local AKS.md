---
publish: true
---
# Adding metrics server to Azure Local in AKS

When running AKS on Azure Local, the metrics server is not included, `k top node` or the metrics in `k9s` do not work.

Add it by:

```yaml
kubectl apply -f https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/components.yaml
```


