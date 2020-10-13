
# exploit ( proxy pass with custom header like X-Correlation-ID)

kubectl apply -f configMap.yml
kubectl apply -f back_deployment.yml
kubectl apply -f back_service.yml
kubectl apply -f front_deployment.yml
kubectl apply -f front_service.yml