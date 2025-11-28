# mark-1
gitops repository for a NextJs Application

# Access teh argo-cd UI

kubectl port-forward -n argocd svc/argcd-server 8080:443

# Access the Application

http://<minikube-ip>:<nodePort>