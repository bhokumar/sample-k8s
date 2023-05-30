kubectl exec -it <podName> bash
psql -d utilizationTracker -U postgres

https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/

# MAC OS installation instruction # 
brew install helm

How to create helm chart
helm create tracker-app

put all objects under template folder

helm install tracker-app --generate-name
helm list
helm uninstall packageName
kubectl exec -it postgresdb-d8bd64bf7-42fcg bash
postgresdb-d8bd64bf7-42fcg


Cheatseat
https://kubernetes.io/docs/reference/kubectl/cheatsheet/