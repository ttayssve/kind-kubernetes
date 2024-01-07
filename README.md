# Kubernetes Study Repository with Kind

## About
This repository is dedicated to studying and experimenting with Kubernetes using Kind (Kubernetes in Docker). Kind allows us to run Kubernetes clusters in Docker containers, making it an ideal tool for development and testing environments.

## Prerequisites
- **Docker**: Ensure Docker is installed and running on your system.
- **kubectl**: The Kubernetes command-line tool, kubectl, allows you to run commands against Kubernetes clusters.

## Installation
1. **Install Kind**: Follow the instructions on the [Kind website](https://kind.sigs.k8s.io/docs/user/quick-start/) to install Kind.
2. **Clone the Repository**: `git clone https://github.com/ttayssve/kind-kubernetes`
3. **Navigate to the Repository**:


## Setting Up Your Kind Cluster
1. **Create a Cluster**: `kind create cluster --name my-cluster`
2. **Set Kubeconfig**: Ensure your kubectl is configured to use the Kind cluster. Usually, Kind does this automatically.

## Exploring Kubernetes with Kind
- **Deploy Applications**: Use `kubectl apply -f` to deploy your applications to the Kind cluster.
- **Monitor Resources**: Use `kubectl get pods, svc, deployments` to monitor your resources.
- **Access Applications**: Understand how to access applications deployed in Kind.

## Examples
This repository includes various examples and manifests to help you understand different Kubernetes concepts and features.

## Contributing
Contributions to this study repository are welcome! Please read our `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgments
- Special thanks to the Kubernetes and Kind communities for their invaluable resources and support.



