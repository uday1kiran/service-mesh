Create a configmap for database credentials using below command.

kubectl create configmap database-config --from-file=.env --kubeconfig=c:\users\username\.kube\config.istio_azure

To check the configmap:
---------
kubectl get configmap --kubeconfig=c:\users\username\.kube\config.istio_azure