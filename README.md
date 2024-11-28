
---

## **Run the below commands in minikube cluster**

  - *kubectl apply -f mongo-secret.yaml*
  - *kubectl apply -f mongo-deployment.yaml*
  - *kubectl apply -f mongo-config.yaml*
  - *kubectl apply -f mongo-express-deployment.yaml*

## **To run mongo express as an external service run**

  - *minikube service mongo-express-service*
    
---
