# K8S-Deployment-Strategies

In Kubernetes we have multiple strategies among them we are discussing few of them here.
---------------------------------------------------
1) Rolling upate:
   -----
   a) It is the default strategy in kubernetes.
   
   b) It incrementally replaces replicaset of old version pods to the new replica set of new pods of new version.
   
   c) By default kubernetes will have maxunavailable and maxsurge is 25% where the rolling updates happens incrementally.
   
   d) It reduces almost downtime while updating new versions of applications. 
   
   
