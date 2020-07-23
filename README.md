# Bugzilla Deployment on k8s Cluster

## Mysql Deployment 
```
git clone https://github.com/kumargaurav522/bugzilla-k8s.git
cd bugzilla-k8s
kubectl apply -f deployment-mysql.yaml
```

After deployment go on Mysql Pod and create bugs database.

## Bugzilla Deployment

```
kubectl apply -f deployment-bugzilla.yaml
kubectl apply -f service.yaml
```
update
