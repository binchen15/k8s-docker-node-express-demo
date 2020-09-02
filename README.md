https://www.youtube.com/watch?v=1xo-0gCVhTU

```
$ docker build -t binchen15/node-web-app .
$ docker run -d -p 3001:3000 binchen15/node-express-demo 

$ kubectl get deployments
$ kubectl get services
$ kubectl get pod

$ kubectl delete deployment node-express-deployment
$ kubectl delete service node-express-service
$ kubectl create -f node-deployment.yaml 

$ minikube dashboard
```

To access the service, there is tunneling, and will choose a different port then you specified.
(refer to https://stackoverflow.com/questions/62375642/minikube-ip-returns-127-0-0-1-kubernetes-nodeport-service-not-accessable)

```
minikube service list
minikube service node-express-service 
```

