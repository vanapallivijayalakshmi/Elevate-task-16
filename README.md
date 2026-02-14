# DevOps Task 16 – Kubernetes Deployment, Scaling & Rollout

## Tools Used
- Ubuntu
- Minikube
- kubectl
- Docker

## What I Did
1. Created Kubernetes Deployment using nginx
2. Verified Deployment and Pods
3. Scaled replicas from 2 to 5
4. Updated image version using rollout
5. Checked rollout history
6. Performed rollback

## Commands Used
kubectl apply -f deployment.yml  
kubectl get deploy  
kubectl get pods -o wide  
kubectl scale deployment nginx-deployment --replicas=5  
kubectl set image deployment/nginx-deployment nginx=nginx:1.26  
kubectl rollout status deployment/nginx-deployment  
kubectl rollout history deployment/nginx-deployment  
kubectl rollout undo deployment/nginx-deployment  

## Outcome
Task 16 completed successfully.
