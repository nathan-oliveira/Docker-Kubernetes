```
docker build -t usuario/flask-kub-projeto .

docker run -d -p 5000:5000 --name flask-kub  --rm usuario/flask-kub-projeto

docker ps

docker push usuario/flask-kub-projeto

kubectl create deployment flask-deployment --image=usuario/flask-kub-projeto

kubectl get deployments
kubectl describe deployments

kubectl get pods
kubectl describe pods
```
