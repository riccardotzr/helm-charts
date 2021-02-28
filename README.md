<div align="center">

# Helm Charts library
</div>

An opinionated collection of Helm Charts.
These charts are created for [Helm v3] and will target [Kubernetes] 1.19.0

## How to use
To use the helm charts you have to add the helm repository and select the chart you want to use:

```bash
helm repo add riccardotzr https://riccardotzr.github.io/helm-charts
helm search repo riccardotzr
helm install release-name riccardotzr/<chart>

```

[Helm v3]: https://helm.sh/docs/intro/install/ (Link for installation guide of Helm v3)
[Kubernetes]: https://kubernetes.io (Production-Grade Container Orchestration)