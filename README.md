# 🚀 Kubernetes Labs for DevOps

![Kubernetes](https://img.shields.io/badge/Kubernetes-Hands--On-blue?logo=kubernetes)
![Status](https://img.shields.io/badge/Status-In_Progress-green)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## 🧠 What I Learned

As part of my DevOps journey, I dedicated time to deeply understand Kubernetes (K8s), which is a critical tool for container orchestration in modern infrastructure.

I studied and implemented real-world labs to practice how Kubernetes works—from deploying simple pods to advanced scheduling, storage, and user management. These labs helped me build hands-on experience with:

- Deployments and pod management  
- Networking with Services  
- Scheduling using Taints, Tolerations, Affinity  
- Volumes, Persistent Storage (PV, PVC, AWS EBS)  
- RBAC and kubeconfig for users  
- Jobs, CronJobs, and Controllers  

Each lab below includes a YAML file and explanation to help replicate or modify the scenario.

---

## 📂 Repository Structure

Each folder in this repository is a **lab** that reflects a specific concept in Kubernetes. The structure follows:


---

## 📚 Lab Index with Short Descriptions

| Lab | Description |
|-----|-------------|
| **lab1** | Create a pod using a YAML manifest. |
| **lab2** | Create a pod with a specific label for future selector matching. |
| **lab3** | Create a new namespace for resource isolation. |
| **lab4** | Create a pod inside a specific namespace. |
| **lab5** | Deploy a ReplicaSet to manage pod replicas. |
| **lab6** | Use a ReplicationController to maintain a pod count. |
| **lab7** | Deploy an application using a Deployment YAML file. |
| **lab8** | Perform a rolling update with a Deployment strategy. |
| **lab9** | Perform a recreate strategy update for a Deployment. |
| **lab10** | Assign a pod to run on a specific node using nodeName. |
| **lab11** | Create a ClusterIP service to expose pods within the cluster. |
| **lab12** | Create a NodePort service to expose pods externally. |
| **lab13** | Create a LoadBalancer service (cloud provider required). |
| **lab14** | Apply taints and tolerations for scheduling control. |
| **lab15** | Use NodeAffinity to control where pods get scheduled. |
| **lab16** | Deploy DaemonSets to run pods on all (or specific) nodes. |
| **lab17** | Define CPU/Memory requests and limits in pod specs. |
| **lab18** | Create a Job to run a task until successful completion. |
| **lab19** | Schedule recurring jobs using CronJob. |
| **lab20** | Use hostPath volume to mount a host directory into the pod. |
| **lab21** | Create a pod using a static PersistentVolume and PVC. |
| **lab22** | Set up dynamic volume provisioning using AWS EBS + StorageClass. |
| **lab23** | Manually configure a static AWS EBS volume as a PV. |
| **lab24** | Create a new kubeconfig context for a normal user. |
| **lab25** | Assign RBAC roles and permissions for the new user context. |

---

## 🛠️ How to Use

1. Clone the repo:
```bash
git clone https://github.com/7khattab/k8s-labs.git
cd k8s-labs

🙌 Connect
If you're learning DevOps or want to discuss K8s labs or improvements, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/mohamed-7khattab) or open an issue here!

