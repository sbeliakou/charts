# Helm Charts

Use this repository to submit official Charts for Kubernetes Helm. Charts are curated application definitions for Kubernetes Helm. 

## Useful Prerequizites

```
helm plugin install https://github.com/zjj2wry/helm-diff
helm plugin install https://github.com/technosophos/helm-template
```

## How do I deploy these charts?

```
helm install --name release-name incubator/jenkins --repo https://github.com/sbeliakou/charts -v override.yaml
```