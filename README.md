# Kubernetes Application Deployment with AutoScaling & Helm

This project demonstrates how to deploy a **containerized application** on **AWS EKS** using **Kubernetes** and **Helm**, including **load balancing, persistent storage**, and **auto-scaling**.

## 🚀 Features
- Kubernetes Deployment with multiple replicas
- Helm chart templating and easy deployment
- LoadBalancer service for external access
- Persistent Volume Claim for data storage
- Horizontal Pod Autoscaler (HPA) for auto-scaling

## 🛠️ Tech Stack
- Kubernetes ☸️
- AWS EKS 🌐
- Helm 🛠️
- Docker 🐳
- Horizontal Pod Autoscaler (HPA)
- Persistent Storage (EBS)

## 💻 Installation & Deployment

1. **Clone the repo**
```bash
git clone https://github.com/yourusername/my-app-chart.git
cd my-app-chart
```

2. **Build and push Docker image**
```bash
docker build -t your-dockerhub-username/my-app:latest .
docker push your-dockerhub-username/my-app:latest
```

3. **Deploy using Helm**
```bash
helm install my-app ./my-app-chart
```

4. **Verify Deployment**
```bash
kubectl get all
kubectl get hpa
```
