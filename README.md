# wscicd

Exemplo de criação de imagem já contendo os arquivos Html na pasta do apache

#Criar imagem do apache e colocar os arquivos na pasta (vai executar o arquivo Dockerfile)

docker build -t meublog .

#Executar novo container a partir da imagem criada
docker run --name blogdocicero -p 8080:80 meublog
