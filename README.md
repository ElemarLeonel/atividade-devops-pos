# Passo a passo para execução do Docker

## builda a imagem
docker build . -t elemar/node-web-app

## verifica se buildou
docker images

## executa 
docker run -p 3000:8080 -d elemar/node-web-app

## valida se esta online
curl -i localhost:3000

