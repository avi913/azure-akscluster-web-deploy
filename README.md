we need to create 1st kubernate service ->create kubernate cluster in azure portel 
after that in bash we need to give below cmd
(az aks get-credentials --resource-group kubernetes --name myakscluster)
(vim aks-store-quickstart.yaml) #create the yaml file
(vim aks-store-quickstart.yaml) #run the cmd
(kubectl get pods) #check all pods are running 
(kubectl get svc) to check all the pods are running or not
(curl -L http://4.224.165.118) # external-ip to get the website 


