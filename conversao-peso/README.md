# conversao-peso

# Fork
https://github.com/KubeDev/conversao-peso

## Build da aplicação:
`docker build -t <nome_imagem> .`

## Executando a aplicação
`docker run -d -p 5000:80 <nome_imagem>`

## Kubernetes
`kubectl apply -f k8s/deployment.yaml`

Para verificar no browser basta acessar: `https://localhost:30000`

## Referência:
https://docs.microsoft.com/pt-br/aspnet/core/host-and-deploy/docker/building-net-docker-images?view=aspnetcore-5.0
