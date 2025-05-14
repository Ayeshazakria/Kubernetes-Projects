**commands for managing replicaSet**</br>

**Pods are managed by ReplicaSet**</br> 
**way-1**</br>
kubectl apply -f replicaset.yml </br>
kubectl get pods </br>
kubectl get rs</br>

**way-2**</br>
kubectl edit rs <rs-name> </br>
kubectl get rs</br>
kubectl get pods </br>

**way-3**</br>
kubectl sacle --replica=2  <rs-name> </br>
kubectl get rs</br>
kubectl get pods </br>

