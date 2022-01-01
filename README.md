# ARMv7 Compatible Helm Charts

This repository contains Helm charts that are compatible for ARMv7 devices, such as the Raspberry Pi 3/4.

## Kubernetes Helm
[Kubernetes Helm](https://github.com/kubernetes/helm) is a package manager for deploying software on a Kubernetes cluster.

## Adding the ARM chart repository

Add the ARM chart repository to Helm:

```
$ helm repo add arm-stable https://github.com/SandraWeddig/arm-charts/tree/master/stable
"arm-stable" has been added to your repositories
```

## Installing ARM charts

Use Helm to install ARM charts:

```
$ helm install arm-stable/mariadb
```

