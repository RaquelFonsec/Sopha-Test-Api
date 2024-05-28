

# Avaliação Sopha
## Para iniciar
Realize um **fork** desse repositório
**clone** o projeto do fork

Execute o comando para provisionar a aplicação:

    $ docker-compose up --build


## Objetivo

 criar uma **API** responsável por gerenciar um catalogo de lojas (**Store**)  e hospedá-lo em uma instância **AWS EC2**.

## Estrutura
Essa **API** possui:

 - Um Model **User** com os atributos **name, email e password**
 - Um Model **Store** com os atributos **name, user_id**
 -  Onde:
	 - **Store** pertence à **User**
	 
## Funcionalidade
As seguintes requisições devem ser possíveis:

 - Processo de autenticação de um **User** (Signup, Signin)
  - Requisições de **CRUD** (Create, Read, Update, Delete) para **Store**  (Estas requisições só devem ser possíveis se o usuário estiver autenticado)


## Conhecimentos necessários
-  Ruby
-  Ruby on Rails
-  AWS EC2
-  Servidores HTTP
-  SQL
-  Postgres 
-   Git

## Requisitos

-   Docker


