# ☸️ Kubernetes Learning & Notes

This repository contains my practical learning notes on Kubernetes.

I'm building this repository to understand Kubernetes concepts step by step, from basic architecture to deployments, networking and troubleshooting.

## 📚 Topics Covered

- Kubernetes Architecture
- Control Plane
- Worker Nodes
- Pods
- Deployments
- ReplicaSets
- Services
- ConfigMaps
- Secrets
- Ingress
- Volumes & Storage
- Namespaces
- Kubernetes Networking
- kubectl Commands
- Troubleshooting
- Kubernetes Interview Questions

## 🏗️ Kubernetes Architecture

A Kubernetes cluster consists mainly of:

### Control Plane 🧠

The Control Plane manages the Kubernetes cluster.

- **API Server** – Entry point for Kubernetes requests.
- **etcd** – Stores cluster configuration and state.
- **Scheduler** – Selects a suitable Worker Node for Pods.
- **Controller Manager** – Ensures the desired state is maintained.

### Worker Node ⚙️

Worker Nodes run our applications.

- **Pod** – Smallest deployable unit in Kubernetes.
- **Container Runtime** – Runs containers.
- **kubelet** – Ensures Pods are running as expected.
- **kube-proxy** – Handles networking and traffic routing.

### 🔄 Basic Flow

User → kubectl → API Server → Scheduler → Worker Node → Pod → Container

## 🎯 Goal

My goal is to build a strong understanding of Kubernetes through hands-on practice and document my learning along the way.

---

#Kubernetes #K8s #DevOps #Docker #Cloud #SRE
