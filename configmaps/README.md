## Kubernetes ConfigMap and Secret as Kubernetes Volumes | Demo
link : https://www.youtube.com/watch?v=FAnQTgr04mU&t=542s&ab_channel=TechWorldwithNana

# ran commands from cmd to create a cluster in eks
1. eksctl create cluster --name test-cluster --version 1.24 --region us-west-2 --nodegroup-name linux-nodes --node-type t2.micro --nodes 2
2. navigate to cd C:\Users\mohad\PycharmProjects\k8_concepts\configmaps and run 
    a. kubectl apply -f config-file.yaml
    b. kubectl apply -f secret-file.yaml
    c. kubectl apply -f mosquitto.yaml