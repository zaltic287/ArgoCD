# ArgoCD sous WSL2

kubectl patch svc argocd-server -n argocd -p '{"spec": {"type": "NodePort"}}'

kubectl port-forward svc/argocd-server -n argocd 8080:443

https://localhost:8080



