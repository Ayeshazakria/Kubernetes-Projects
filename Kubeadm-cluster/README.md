**commands for managing replicaSet**

#Pods are managed by ReplicaSet 
**way-1**
kubectl apply -f replicaset.yml </br>
kubectl get pods </br>
kubectl get rs</br>

**way-2**
kubectl edit rs <rs-name> </br>
kubectl get rs</br>
kubectl get pods </br>

**way-3**
kubectl sacle --replica=2  <rs-name> </br>
kubectl get rs
kubectl get pods 

