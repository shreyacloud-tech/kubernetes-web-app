# Kubernetes Web Application Deployment

## 📌 Project Overview

This project demonstrates deploying a containerized web application on Kubernetes using a Deployment and a NodePort Service.

The application is deployed locally using Minikube with Nginx as the web server.

## 🛠️ Technologies Used

- Kubernetes
- Minikube
- Docker
- Nginx
- YAML

## ☸️ Kubernetes Concepts Implemented

- Pods
- Deployments
- Replicas
- Services
- NodePort
- Kubernetes YAML Manifests

## 📂 Project Files

- `deployment.yaml` — Defines the Kubernetes Deployment and Pod configuration
- `service.yaml` — Defines the NodePort Service used to expose the application
- `README.md` — Project documentation

## 🚀 Deployment Commands

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl get pods
kubectl get services
minikube service my-web-service

## Outcome

Successfully deployed an application on Kubernetes with 2 running pods and exposed it using a NodePort service.
