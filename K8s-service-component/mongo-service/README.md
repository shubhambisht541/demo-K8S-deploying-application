The service in K8s used to manage the deployment and it is used as it
- Provides a static ip which helps in internal communication between services in K8s cluster
- Provides load balencing, to forward request to the appropirate pod in the deployment 


## *Run the below commands in minikube cluster*
    kubectl apply -f mongo-secret.yaml
    kubectl apply -f mongo-deployment.yaml
    kubectl apply -f mongo-config.yaml
    kubectl apply -f mongo-express-deployment.yaml

## To run mongo express as an external service run**
    minikube service mongo-express-service
    

