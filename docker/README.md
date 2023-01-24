# Projeto conversão de temperatura

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

### Para montar a imagem execute
docker build -t seu-repo/conversao-temperatura:v1 .

### Para subir o container execute
docker run -itd --name conversaotemp -p 8080:8080 seu-repo/conversao-temperatura:v1
