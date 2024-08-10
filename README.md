# K8S
minikube start
kubectl apply -f .\flask-deployment.yml
kubectl apply -f .\flask-service.yml
kubectl get pods
kubectl get services
kubectl describe pod flaskapp-deployment-6c54d76bdd-2l62v
kubectl get services
kubectl describe service flaskapp-service
kubectl get pods
minikube service flaskapp-service

------------------------------
minikube ip
kubectl get svc
------------------------------
kubectl port-forward service/flaskapp-service 5000:5000

----------------------------------------------
minikube stop

---------------------------------------------