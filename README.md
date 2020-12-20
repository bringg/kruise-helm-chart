# Kruise unofficial Helm repo

OpenKruise only supports Kubernetes version >= `1.13+` because of CRD conversion.
Note that for Kubernetes 1.13 and 1.14, users must enable `CustomResourceWebhookConversion` feature-gate in kube-apiserver before install or upgrade Kruise.

## Installing

### Add the kruise Helm charts repo

```shell
helm repo add kruise https://raw.githubusercontent.com/bringg/kruise-helm-chart/master
```

### Install it

- with Helm 3: `helm install kruise/kruise`
- with Helm 2 (deprecated): `helm install --name kruise kruise`

### References
- [OpenKruise](https://openkruise.io)
- [Helm Chart documentation (0.7.0)](https://github.com/openkruise/kruise/tree/master/charts/kruise/v0.7.0)
