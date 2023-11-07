# k8s-wordpress

- k3d cluster create mysql-wordpress -p 80:80@loadbalancer -p 3306:3306@loadbalancer
- kubectl apply -k ./

- Acessar a aplicação em http://wordpress.localdev.me