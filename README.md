# Loja Veloz - Microserviços

## Rodar local

docker compose up --build

## Kubernetes

kubectl apply -f k8s/

## Testar

kubectl port-forward service/pedidos 3000:80

Acessar:
http://localhost:3000

## Serviços

* Pedidos
* Pagamento
* Estoque

## Tecnologias

* Node.js
* Docker
* Kubernetes
