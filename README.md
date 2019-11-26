# Get Started
## with these commands
kubectl apply -f ./<secret yaml file name>
kubectl get services
kubectl apply -f ./<env pod yaml file name>
kubectl get pods
kubectl exec -it <pod name> sh
echo $<env var name>
exit
kubectl apply -f ./<volume pod yaml file name>
kubectl get pods
kubectl exec -it <pod name> sh
cd /etc/foo
ls		# must show w files: username and password
cat username
cat password
## Clean up
kubectl delete deployments/<deployment name>
kubectl delete secrets/<secret name>
