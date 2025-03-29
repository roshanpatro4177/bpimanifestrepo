start in sequence

kubectl apply -f configmap.yaml
kubectl apply -f secret.yaml

kubectl apply -f pv.yaml
kubectl apply -f pvc.yaml


kubectl apply -f postgres-deployment.yaml
kubectl apply -f mongo-deployment.yaml
kubectl apply -f neo4j-deployment.yaml
kubectl apply -f <app-deployment>.yaml
