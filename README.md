# Kubernetes Web Application Deployment

## Project Overview

This project demonstrates deploying a web application on Kubernetes using Deployments and Services.

## Technologies Used

* Kubernetes
* Minikube
* Docker
* Nginx

## Concepts Implemented

* Deployments
* Pods
* Replicas
* Services
* NodePort

## Files

* deployment.yaml
* service.yaml
* README.md

## Commands Used

kubectl apply -f deployment.yaml

kubectl apply -f service.yaml

kubectl get pods

kubectl get services

minikube service my-web-service

## Outcome

Successfully deployed an application on Kubernetes with 2 running pods and exposed it using a NodePort service.
