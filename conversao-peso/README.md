# conversao-peso

## Build da aplicação:
docker build -t <nome_imagem> .

## Executando a aplicação
docker run -d -p 5000:80 <nome_imagem>

## Kubernetes
docker run --rm mcr.microsoft.com/dotnet/aspnet printenv

## Referências:
https://docs.microsoft.com/pt-br/aspnet/core/host-and-deploy/docker/building-net-docker-images?view=aspnetcore-5.0