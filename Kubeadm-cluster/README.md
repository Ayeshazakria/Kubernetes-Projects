**commands for managing replicaSet**</br>

**Pods are managed (created,scaled,edited,deleted) by ReplicaSet (controller object)**</br> 
**way-1(through .yml files)***</br>
kubectl apply -f replicaset.yml </br>
kubectl get pods </br>
kubectl get rs</br>

**way-2(through live object already created in yml)**</br>
kubectl edit rs <rs-name> </br>
kubectl get rs</br>
kubectl get pods </br>

**way-3(through command line)**</br>
kubectl scale --replica=2  <rs-name> </br>
kubectl get rs</br>
kubectl get pods </br>


**Pods are managed by Deployment ( bigger subset of ReplicaSet ) ** </br>

**way-1 (through .yml files)**  </br>
kubectl apply -f deployment.yml </br>
kubectl get pods </br>
kubectl get deployment</br>

**way-2 (through live object already created in yml)**</br>
kubectl edit deployment <rs-name> </br>
kubectl get deployment</br>
kubectl get pods </br>

**way-3 (through command line)**</br>
kubectl scale --replica=2  <deployment-name> </br>
kubectl get deployment</br>
kubectl get pods </br>

