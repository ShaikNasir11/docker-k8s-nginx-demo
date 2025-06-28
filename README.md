# Docker + Kubernetes Nginx Demo

This project demonstrates:
- Building a Docker image for a simple Nginx web server.
- Deploying it on a Kubernetes cluster using Deployment and Service.
- (Optional) Exposing it via Ingress Controller.

## Commands
- docker build -t nginx-demo .
- kubectl apply -f k8s/
- kubectl get pods, svc


