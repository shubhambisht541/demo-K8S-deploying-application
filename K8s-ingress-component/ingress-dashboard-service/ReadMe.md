The ingress component in K8s is used to communicate with external service. The ingress can be setup in two steps:
- Create an ingress component file that will contain the rule set which configure which domain address will map to which service
- Ingress controller which will manage to run those rule sets for ingress component


## *Install ingress controller in minikube cluster*
    minikube addons enable ingress

## *Run dashboard service in kubernetes-dashboard namespace*
    minikube dashboard

## *Apply ingress configuration file*
    kubectl apply -f dashboard-ingress.yaml

## *Map the localhost ip address 127.0.0.1 to dashboard.com domain*
    sudo vim /etc/hosts

## *Run the tunnel to run ingress component*
    minikube tunnel