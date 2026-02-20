# container-orchestration-lab
# Microservices Orchestration with K8s & Docker

## Project Summary
This project shows how to use **Docker** to package an application into a container. I then used **Kubernetes** to manage those containers, ensuring the app stays running even if something breaks.

* **Languages Used:** YAML, Bash.
* **Environments Used:** Kubernetes Cluster (Local or Cloud).
* **Technologies Used:** Docker, Kubernetes (K8s), kubectl.

---

## 🛠️ Implementation Steps
1. **Containerizing the App:** Created a "Dockerfile" to turn my project into a **Docker Image**.
2. **Kubernetes Deployment:** Wrote code to tell Kubernetes how many copies of my app to keep running.
3. **Self-Healing Test:** I "deleted" a working app, and showed that Kubernetes automatically made a new one to replace it in seconds!
