# Projeto: Integrando Python com SQLite e MongoDB

O uso de banco de dados permeia diversos âmbitos da computação. Por esse motivo realizar integração das
aplicações, em diferentes linguagens de programação, e banco de dados se torna de suma importância. Este projeto possui duas 
partes bem definidas. Na primeira parte iremos utilizar integração com banco de dados relacional, enquanto que na segunda parte 
iremos entrar no mundo dos não relacionais orientados a documentos.
[(clique aqui para ver o meu perfil na plataforma)](https://web.dio.me/users/guih_gabriel93?tab=achievements)
#### Tecnologia: Python
#### Data: 22/10/2022


Parte 1 - IntegracaoComSQL

Nesta parte nosso projeto está focado na utilização do SQLAlchemy para criação de um esquema simples dentro do SQlite. Adotamos
o SQlite como opção de banco de dados para simplificação do setup. Sendo assim nesta estapa utilizaremos dois modelos
disponibilizados pelo framework:

-> ORM
-> CORE 

O ORM - Object Relational Mapping - consiste em um modelo orientado a domínio onde não estaremos lidando com a linguagem de
consulta de banco de dados - SQL - diretamente. O ORM realiza o mapeamento entre o mundo relacional e orientação à objeto. 
Em sentido contrário, o CORE estará disponibilizando o acesso direto ao SQL. Sendo assim, diferentemente do ORM este modelo
é orientado a esquema (foco no SQL).

Parte 2 - IntegracaoComMONGO

Utilizaremos o módulo pymongo criado e mantido pela equipe de Python do MongoDB. Sendo assim, iremos criar o banco de dados, 
coleções, documentos utilizando o pymongo em conjunto com MongoDb Atlas. As configurações para acesso do cluster estão 
definidas dentro da aplicação.
