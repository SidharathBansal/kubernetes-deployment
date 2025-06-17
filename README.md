# Kubernetes Deployment Flow Visualization 🌐

This repository hosts an interactive HTML visualization of how a `deployment.yaml` gets processed inside Kubernetes — from applying the YAML to running pods on nodes.

🚀 **Live Demo**  
👉 [View the visualization here](https://<your-github-username>.github.io/<repo-name>/)

---

## 📌 What This Covers

This flowchart visualizes the internal components and steps involved in a Kubernetes deployment:

1. User applies a `deployment.yaml`
2. API Server processes the request and stores it in etcd
3. Deployment Controller creates a ReplicaSet
4. ReplicaSet Controller spawns Pods
5. Scheduler assigns Pods to Nodes
6. Kubelet, CNI, and container runtime handle actual execution

---

## 🛠 Tech Stack

- HTML/CSS (no JavaScript or frameworks)
- GitHub Pages for hosting
- Interactive UI with hover effects for better learning

---

## 📁 File Structure

```bash
.
├── index.html       # Main visualization file
├── README.md        # This file
