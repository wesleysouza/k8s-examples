# Exemplo de Deploy com Ingress

Deploy de aplicação utilizando um serviço ClusterIP e um Ingress (NodePort).

## Apps

### Java

Endpoints:
 - /

### DotNet

Endpoints:
 - /

### Flask

Endpoints:
 - /
 - /messages/{id}

## Imagens docker
- wesleysouzasci/java-dummy-app:1.0
- wesleysouzasci/dummy-dotnet:1.0
- wesleysouzasci/flask-dummy-app:1.0