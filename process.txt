Go to the aws folder 
kubectl create -f deploy.yaml

then

kubectl get ns
kubectl -n ingress-nginx get svc

copy the loadbalancer endpoint 
try to browser then u will get 401 nginx error

after that u write ingress rule
===================================================================
vi ingress.yaml
