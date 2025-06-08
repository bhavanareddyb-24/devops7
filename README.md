@@ -1 +1,88 @@
# devops7
# 🚀 Task 5 - Kubernetes with Minikube

## 📌 Objective
Deploy and manage a sample application locally using Kubernetes with Minikube, demonstrating key concepts like deployments, services, scaling, and logging.

---

## 🛠 Tools Used
- [Minikube](https://minikube.sigs.k8s.io/)
- [kubectl](https://kubernetes.io/docs/reference/kubectl/)
- [Docker](https://www.docker.com/)

---

## 📂 Project Structure

. ├── deployment.yaml       # Kubernetes Deployment configuration ├── service.yaml          # Kubernetes Service configuration ├── screenshots/          # Output screenshots │   ├── pods.png │   ├── services.png │   └── scale.png └── README.md             # Project documentation

---

## ⚙ Steps Performed

1. *Started Minikube cluster*
   ```bash
   minikube start

2. Created deployment.yaml to deploy an Nginx app.


3. Created service.yaml to expose the deployment using a NodePort.


4. Verified pod and service creation

kubectl get pods
kubectl get svc


5. Scaled the deployment to 4 replicas

kubectl scale deployment nginx-deployment --replicas=4


6. Described the deployment for log inspection

kubectl describe deployment nginx-deployment




---

🖼 Screenshots

🔹 Pods



🔹 Services



🔹 Scaling




---

🎓 Learning Outcome

Gained hands-on experience with:

Creating and managing Kubernetes deployments and services

Using Minikube for local cluster setup

Scaling applications and monitoring Kubernetes resources



---

📎 Author

Your Name Here

Let me know if you want this customized with your name or any changes!
