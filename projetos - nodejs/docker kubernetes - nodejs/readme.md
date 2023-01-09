docker build -t node-hash .

docker images

docker run -p 3000:3000 node-hash
docker stop vibrant_euclid

docker vibrant_euclid

kind create cluster
kubectl get nodes
kind load docker-image node-hash

kubectl apply -f kubernetes/manifests.yaml

kubectl get deploy
kubectl get pods
kubectl deploy/hash-api
kubectl port-forward service/hash-api 3000:80
