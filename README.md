# Springboot-Restfull-WebServices

## :memo: Descrição

API para criar, recuperar, atualizar e excluir um usuário e, em seguida, testando usando o Postman.

## :books: Funcionalidades

## - Criar entidade JPA - User.java

- ``id - chave primária``
- ``firstName - nome do usuário``
- ``lastName - sobrenome do usuário``
- ``e-mail - ID de e-mail do usuário``

## - Criar repositório Spring Data JPA para entity JPA do User

Criado um  UserRepository  para acessar os dados do usuário no banco de dados.
Bem, Spring Data JPA vem com uma  interface JpaRepository  que define métodos para todas as operações CRUD
na entidade e uma implementação padrão de  JpaRepository  chamada  SimpleJpaRepository.

## - Implementação da Camada de Serviço | UserService, UserServiceImpl

Esta camada conterá a lógica de negócios da API e será usada para realizar operações CRUD usando o Repositório.

## -  UserController

O controlador é responsável por lidar com as solicitações HTTP recebidas e retornar a resposta apropriada.
Você precisará definir os endpoints da API e mapeá-los para os métodos apropriados na camada de serviço.

## :wrench: Tecnologias utilizadas

- ``Spring Boot 3``
- ``Spring Data JPA`` 
- ``Banco de dados MySQL``

## :rocket: Rodando o projeto

Para rodar o repositório é necessário clonar o mesmo, dar o seguinte comando para iniciar o projeto:
```
Abra seu terminal ou Git <git clone "A url do projeto"> 
```
