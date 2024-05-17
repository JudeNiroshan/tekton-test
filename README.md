# Simple Tekton Test Project 🚀

This project demonstrates a basic Tekton pipeline that clones a Git repository and prints a message. Entrypoint is simple-pipeline-run.yaml

## Prerequisites 📋

- Kubernetes cluster with Tekton installed
- `kubectl` or `oc` configured to interact with your cluster

## Installation 🛠️

1. **Install Red Hat OpenShift Pipelines**:

It can be easily installed into OCP via the Operator Hub

2. **Clone the Repository**:
    ```sh
    git clone https://github.com/judeniroshan/simple-tekton-test-project.git
    cd simple-tekton-test-project
    ```

3. **Apply Tekton Resources**:
    ```sh
    oc apply -f .
    ```

