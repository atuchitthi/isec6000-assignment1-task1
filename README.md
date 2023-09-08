# Setting Up Initial Infrastructure

This README provides step-by-step instructions on how to set up the initial infrastructure for your project. Follow these steps to create a Kubernetes cluster on Google Cloud Platform (GKE), install and configure `kubectl`, and set up a private GitHub repository for your project files.

## 1. Create a Kubernetes Cluster on GKE

### a. Create a Google Cloud Project

- Log in to your Google Cloud account.
- Create a new project for your infrastructure setup.
  ![image](https://github.com/atuchitthi/isec6000-assignment1-task1/assets/143305032/6a129e46-9ea7-40b9-8b18-99eacedb967c)

### b. Create a GKE Cluster

- After creating the project, navigate to Google Kubernetes Engine (GKE).
  ![image](https://github.com/atuchitthi/isec6000-assignment1-task1/assets/143305032/84dffc29-c193-4a97-9710-590651c86240)

- Create a cluster named `isec6000-cluster-task1`, and configure cluster settings, including name, location, and node pool configuration. Choose the desired Kubernetes version.
- Click "CREATE."
  ![image](https://github.com/atuchitthi/isec6000-assignment1-task1/assets/143305032/1995fe85-2d09-46a2-b390-27bf7bf62e82)
  ![image](https://github.com/atuchitthi/isec6000-assignment1-task1/assets/143305032/7870607f-df89-4ac8-bf56-7f527869d0ac)
  ![image](https://github.com/atuchitthi/isec6000-assignment1-task1/assets/143305032/77ef0846-903b-440b-b03b-804a772b04a9)

## 2. Install and Configure `kubectl`

[Kubectl](https://kubernetes.io/docs/reference/kubectl/) is a command-line tool for managing Kubernetes clusters. Follow these steps to install and configure it:

### a. Connect GKE Cluster

- After creating the GKE cluster, connect the cluster to the Kubernetes engine. This will configure your local environment to use `kubectl` to interact with the cluster.
  ![image](https://github.com/atuchitthi/isec6000-assignment1-task1/assets/143305032/7a4c53cc-5a00-49b4-add2-9a35f2f877ba)
  ![image](https://github.com/atuchitthi/isec6000-assignment1-task1/assets/143305032/e04aeb25-2f9e-4da8-ba7e-42f9895157e9)
  ![image](https://github.com/atuchitthi/isec6000-assignment1-task1/assets/143305032/64b27d90-9985-4ff2-b2ca-4d52b0d8e6ed)

### b. Authorize the Cluster

- An authorization popup will appear, asking you to authorize the cluster with Cloud Shell.
  ![image](https://github.com/atuchitthi/isec6000-assignment1-task1/assets/143305032/5300e13b-8222-4419-80b1-4943e3589af8)
  ![image](https://github.com/atuchitthi/isec6000-assignment1-task1/assets/143305032/ba7e4ff3-7cd5-4524-85f7-c455f8dd9c57)

## 3. Set Up a Private GitHub Repository

### a. Create a GitHub Repository

- Log in to your GitHub account.
- Create a new repository named `isec6000-assignment-task1`. Make sure to set it as a private repository to store your project files.
  ![image](https://github.com/atuchitthi/isec6000-assignment1-task1/assets/143305032/6109f000-64ab-442d-baee-c9a6572c2e10)
