# Kubernetes Beginner Cheat Sheet

---

## 1. What is Kubernetes?
Kubernetes is an open-source platform designed to automate deploying, scaling, and operating application containers.

---

## 2. Key Terminology

- **Cluster**: A set of nodes (machines) that run containerized applications managed by Kubernetes.

- **Node**: A physical or virtual machine in the Kubernetes cluster. Each node runs at least one container runtime, such as Docker.

- **Pod**: The smallest deployable unit in Kubernetes, which can contain one or more containers that share storage, networking, and a specification for how to run the containers.

- **Namespace**: A virtual cluster within a Kubernetes cluster. Namespaces are used to divide cluster resources between multiple users or applications, allowing for resource isolation.

- **ReplicaSet**: Ensures that a specified number of pod replicas are running at all times. It can be used to scale pods up or down.

- **Deployment**: A higher-level abstraction that manages ReplicaSets and provides declarative updates to pods. It ensures that the desired state (number of replicas, container images, etc.) is maintained.

- **Service**: An abstraction that defines a logical set of pods and a policy for accessing them. Services enable communication between different parts of an application.

- **ConfigMap**: A way to inject configuration data into pods at runtime, allowing applications to be decoupled from configuration details.

- **Secret**: Similar to ConfigMap but intended for sensitive information, such as passwords or tokens. Secrets are encoded to provide a level of security.

- **Volume**: A storage resource in Kubernetes, allowing data to persist beyond the lifecycle of individual pods. Volumes can be backed by various storage types, such as local disks, NFS, or cloud storage.

- **Ingress**: An API object that manages external access to services, typically HTTP. It provides features such as load balancing, SSL termination, and name-based virtual hosting.

- **Horizontal Pod Autoscaler (HPA)**: Automatically scales the number of pods in a deployment or replica set based on observed CPU utilization or other select metrics.

---

## 3. Additional Concepts

- **Helm**: A package manager for Kubernetes that helps manage Kubernetes applications through Helm charts, which are collections of pre-configured Kubernetes resources.

- **Kubelet**: An agent that runs on each node in the cluster, responsible for managing the pods and containers running on that node.

- **Kube-Proxy**: A network proxy that maintains network rules on nodes, allowing communication to services.

- **Persistent Volume (PV)**: A piece of storage in the cluster that has been provisioned by an administrator or dynamically provisioned using Storage Classes.

- **Persistent Volume Claim (PVC)**: A request for storage by a user. It can specify size and access modes.

---
