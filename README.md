# gitops-fluxcd
Flux the GitOps operator for Kubernetes

### The Flux workflow
Flux is a tool that automatically ensures that the state of your Kubernetes cluster matches the configuration you’ve supplied in Git. It uses an operator in the cluster to trigger deployments inside Kubernetes, which means that you don’t need a separate continuous delivery tool.


In this repository we will use the following tools:

- Terraform
- Ansible
- Kubernetes
- Helm
- Docker
- Python