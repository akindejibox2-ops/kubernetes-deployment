# Kubernetes Deployment Project

This repo contains Kubernetes manifests and a Helm chart for deploying a sample application.

## Features
- Kubernetes deployment & service
- Ingress routing
- Namespace isolation
- Helm chart packaging

## Tools Used
Kubernetes, Docker, Helm, YAML

## How to Apply Manifests
kubectl apply -f namespace.yaml  
kubectl apply -f deployment.yaml  
kubectl apply -f service.yaml  
kubectl apply -f ingress.yaml  

## Helm Deployment
helm install sample-app ./helm-chart
