# pintu-nodejs

This repository contains a simple Node.js application that is deployed using Docker and Kubernetes manifest files on Minikube. The use of self-hosted runners for GitHub Actions enhances security and manageability, especially when dealing with sensitive credentials and the potential for future scalability.

## Technology Stack

- **Node.js**: The application is built with Node.js, a popular JavaScript runtime for server-side applications.

- **Docker**: Docker is used to containerize the Node.js application. This simplifies deployment and ensures consistent behavior across different environments.

- **Kubernetes**: Kubernetes manifests are provided to deploy the containerized application on Minikube or other Kubernetes clusters, whether in a local development environment or in the cloud.

- **GitHub Actions**: GitHub Actions are used for automation. A self-hosted runner is employed to enhance security and manage credentials more effectively.

## Why These Technologies?

- **Docker**: Docker allows you to package the application along with its dependencies into a container image, making it easier to deploy consistently in various environments. 

- **Self-Hosted Runner**: Using self-hosted runners for GitHub Actions provides a more secure and manageable way to execute workflows, especially when dealing with sensitive credentials and secrets. It also offers better control over your CI/CD environment.

- **Kubernetes Manifests**: Using simple Kubernetes manifests for deployment is an effective way to manage the application's lifecycle. For enhanced security, Helm charts can be employed for more complex deployments.

## Getting Started

1. Clone this repository to your local machine:

   ```sh
   git clone https://github.com/your-username/pintu-nodejs.git
   cd pintu-nodejs