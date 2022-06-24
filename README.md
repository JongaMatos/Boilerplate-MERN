# Boilerplate MERN

Este repósitório se trata de um boilerplate para a criação de aplicações com o uso da stack MERN (Mongo, Express, React, NodeJs), e typescrpt.

## Docker

Ao rodar o docker, serão iniciados o frontend, o backend e o banco de dados.

O docker esta configurado considerando que ambos o frontend e o backend utilizam o yarn, então este é o gerenciador de pacotes recomendado.

### Comandos

1. `sudo docker-compose build` : este comando constroe uma imagem do docker, e precisa ser utilizado antes de iniciar o docker da aplicação pela primeira vez, e novamente após instalar novas bibliotecas no projeto.
2. `sudo docker-compose up` : este comando irá iniciar o docker, fazendo com que o frontend, o backend, e o banco de dados sejam iniciados.
3. `sudo docker-compose up --build` : este comando é o equivalente a rodar o comando ***1*** e depois o comando ***2***.
4. `sudo docker-compose down` : este comando irá limpar o banco de dados, apagando todos os dados contidos no mesmo.
