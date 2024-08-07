# Kustomize Manifests for Rocket AI Hub on ppc64le
A repository for Kustomize manifests for Rocket AI Hub on IBM Power (ppc64le).
These manifests base on the [official Kubeflow manifests](http://www.github.com/kubeflow/manifests/).

## Supported Distributions
- Red Hat OpenShift v4.14 on ppc64le

## Supported Environment
- Tested on IBM Techzone P9/P10 Environment with minimum 4 cores and 128G memory

## Install
```
KUBEFLOW_VERSION=main
wget https://raw.githubusercontent.com/xjasonliu/RocketAIHub-v1.7.0/blob/${KUBEFLOW_VERSION}/install_kubeflow.sh
source install_kubeflow.sh
```




