# kubernetes
#commandes utilisées pour le TP1/
       #pod

- kubectl --version
- kubectl get nodes 
- kubect-l get pod
- kubectl apply -f pod.yaml
- kebectl port-forward simple-app 5000:8080 --address 0.0.0.0
- kubectl describe pod pod.yaml
- kubectl delete -f pod.yaml
- kubectl delete pod simple-app

       #Deployment

- kubectl apply -f nginx_deploiement.yml
- kubectl describe deployment nginx-pod
- kubectl get replicaset
- kubectl get replicaset -o wide
- kubectl get pod 
- kubectl get deployment
- kubectl get nodes 
- kubectl port-forward <name_pod>  5000:80 --address 0.0.0.0  

