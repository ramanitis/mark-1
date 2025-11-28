# mark-1
gitops repository for a NextJs Application

# Access the argo-cd UI

kubectl port-forward -n argocd svc/argocd-server 8080:443

# Access the Application

http://<minikube-ip>:<nodePort>
