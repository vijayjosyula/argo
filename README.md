# argo
ArgoCD installation and a simple application management
https://mycloudjourney.medium.com/argocd-series-how-to-install-argocd-on-a-single-node-minikube-cluster-1d3a46aaad20

kubectl delete all --all -n argocd

#version of argo that ran successfully
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/v2.3.12/manifests/install.yaml
