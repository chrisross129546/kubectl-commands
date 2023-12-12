kubectl KUBECONFIG=config.yaml - prepares the terminal for the right server, you would use this if the terminal is in the servers folder but no servers are selected/n
kubectl get pods - views the pods for whichever server is currently selected/n
kubectl rollout restart deploy [POD] - restarts a particular pod (copy the id from when you use kubectl get pods and replace [POD] with said id)/n
kubectl logs [POD] - checks the logs coming from a pod, often useful when restarting a pod to make sure everything works out fine\n
kubectl apply -f [FILE] - when modifying a file from a server use this to save the changes (ensure you are looking at the right pod (use kubectl get pods to make sure))\n
kubectl describe [POD] - describes a particular pod\n
