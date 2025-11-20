# Basic Kubernetes Interview Questions

## 1. What is Kubernetes?
 - Kubernetes is an open-source container orchestration platform.
 - It automates deployment, scaling, and management of containerized applications.

## 2. What is a Pod in Kubernetes?
 - A pod is the smallest deployable unit in Kubernetes.
 - It can contain one or more containers that share storage and network.

## 3. What is a ReplicaSet?
 - Ensures a specified number of identical pods are running at any time.
 - Automatically replaces crashed or deleted pods.

## 4. What is the difference between a Pod and a Deployment?
 - Pod is a single instance of a running container.
 - Deployment manages a ReplicaSet, which manages Pods — it ensures desired state, handles updates/rollbacks.

## 5. What is a Service in Kubernetes?
 - Abstracts access to a set of Pods.
 - Provides stable network endpoint (ClusterIP, NodePort, LoadBalancer).

## 6. What are the types of Services in Kubernetes?
 - ClusterIP: default, internal access only.
 - NodePort: exposes pod via static port on each node.
 - LoadBalancer: exposes app using external cloud load balancer.
 - ExternalName: maps to external DNS name.

