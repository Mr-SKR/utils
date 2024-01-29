# utils

## insecured-k8s-dashboard
Run kubernetes dashboard locally:

- kubectl apply -f https://raw.githubusercontent.com/Mr-SKR/utils/main/indecured-k8s-dashboard.yaml
- kubectl -n kubernetes-dashboard create token admin-user copy the resultant token value to use in step 4
- kubectl proxy
- Open this [url](http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/) in browser and use token from step 2
