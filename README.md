
- **frontend/**: Contains Kubernetes manifests for deploying the frontend application.
- **backend/**: Contains Kubernetes manifests for deploying the backend services.

---

## 🚀 Prerequisites

Ensure the following are installed and configured:

- [Docker](https://www.docker.com/)
- [Kubernetes](https://kubernetes.io/) cluster (e.g., Minikube, EKS, GKE)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)


---

## ⚙️ Deployment Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/M-Samii/K8S-3-Tier-App.git
   cd K8S-3-Tier-App

Deploy the Backend

      kubectl apply -f backend/deployment.yaml
      kubectl apply -f backend/service.yaml
      
Deploy the Frontend

    kubectl apply -f frontend/deployment.yaml
    kubectl apply -f frontend/service.yaml
    
🔍 Verification

    kubectl get pods
    kubectl get services
