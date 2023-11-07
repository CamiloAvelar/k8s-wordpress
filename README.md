# k8s-wordpress

- k3d cluster create mysql-wordpress -p 8000:80@loadbalancer -p 8001:30001@loadbalancer
- kubectl apply -k ./

- Acessar a aplicação em http://localhost:8000