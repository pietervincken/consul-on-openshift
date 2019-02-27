# consul-on-openshift

## Steps

1. Clone [Consul Helm repository](https://github.com/hashicorp/consul-helm.git)
    - `git clone https://github.com/hashicorp/consul-helm.git`
2. Start minikube
    - `minikube start`
3. Install Consul on Vanilla Kube
    - `helm upgrade --install -f openshift-consul-values.yaml --name consul ./consul-helm `
