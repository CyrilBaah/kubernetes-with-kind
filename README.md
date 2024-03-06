# Kubernetes with Kind
Tools and manifest files for running kubernetes locally.

## How to set up locally using Docker container - **Recommended**
### Prerequisite
- Make sure **Docker** is installed locally. *Checkout installation here* [Docker](https://www.docker.com/ "Docker")
- Make sure **Kind** is installed locally. *Checkout installation here* [Kind](https://kind.sigs.k8s.io/ "Kind")

1. Set up Kubernetes environment
```sh
 kind create cluster --config kind-cluster-config.yaml
```