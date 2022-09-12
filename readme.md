# kubectl apply commands in order
    
    kubectl apply -f mongo-secret.yaml
    kubectl apply -f mongo.yaml    
    kubectl apply -f mongo-configmap.yaml 
    kubectl apply -f mongo-express.yaml
    
### Find a URL to external service in minikube

 minikube service mongo-express-service

### kubectl get commands

    kubectl get pod
    kubectl get pod --watch
    kubectl get pod -o wide
    kubectl get service
    kubectl get secret
    kubectl get all | grep mongodb

### kubectl debugging commands

    kubectl describe pod mongodb-deployment-xxxxxx
    kubectl describe service mongodb-service
    kubectl logs mongo-express-xxxxxx

 
    
    
    Details: https://www.youtube.com/watch?v=EQNO_kM96Mo
