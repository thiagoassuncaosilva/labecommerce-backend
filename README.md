# Projeto Labecommerce

First project integrante da iniciação do back-end, onde praticamos toda a base de criação de uma API vinculada a um banco de dados real.

## Conteúdos abordados

- NodeJS
- Typescript
- Express
- SQL e SQLite
- Knex
- Postman

# Banco de dados
![image](https://user-images.githubusercontent.com/29845719/214396608-ddcfd097-e615-44f9-acbe-f815f9abb83f.png)
https://dbdiagram.io/d/63c6e8e5296d97641d7a4666

## URLs de acesso
Documentação da API com as instruções de uso de cada endpoint da aplicação Labecommerce.<br>

[Labecommerce API](https://documenter.getpostman.com/view/26592309/2s946h9sj6)

# Lista de requisitos

- Endpoints

    - [ ]  Create user
    - [ ]  Get all users
    - [ ]  Edit user by id
    - [ ]  Delete user by id
    - [ ]  Create product
    - [ ]  Get all products
    - [ ]  Get product by name
    - [ ]  Get product by id
    - [ ]  Edit product by id
    - [ ]  Delete product by id
    - [ ]  Create purchase
    - [ ]  Edit purchase by id
    - [ ]  Get all purchases
    - [ ]  Get purchase by id
    - [ ]  Delete purchase by id

# Exemplos de requisição
Não precisa cadastrar o mesmo nome, email e quaisquer outros valores vistos aqui nos exemplos de saída. Porém, lembre-se de respeitar a estrutura pedida no banco de dados (nome das tabelas e colunas) e os nomes das propriedades na resposta da API.

Colunas a mais na tabela não tem problema, por exemplo adicionar uma 'category' dentro da tabela 'products', mas a falta de uma coluna ou propriedade na resposta será considerada falha de implementação!

## Métodos
Requisições para a API devem seguir os padrões:
| Método | Descrição |
|---|---|
| `GET` | Retorna informações de um ou mais registros. |
| `POST` | Utilizado para criar um novo registro. |
| `PUT` | Atualiza dados de um registro ou altera sua situação. |
| `DELETE` | Remove um registro do sistema. |


## Respostas

| Código | Descrição |
|---|---|
| `200` | Requisição executada com sucesso (success).|
| `201` | Dados creado com sucesso(sucess).|
| `400` | Erros de validação ou os campos informados não existem no sistema.|
| `404` | Registro pesquisado não encontrado (Not found).|
| `500` | Erro inesperado.|


## Iniciando 

Esse é um exemplo das intruções de como você configura o projeto localmente.
Para ter uma copia local, siga os passos abaixo:

### Instalação
   
1. Install NPM TypeScript packages 
  ```sh
  npm init -y (cria package.json)
  ```
  ```sh
  npm i -g typescript (faz só 1 vez)
  ```
  ```sh
  npm i typescript -D (instala typescript no projeto)
  ```
  ```sh
  npx tsc -init (criar tsconfig.json)
  ```
  
2. Install NPM Express packages 
  
  ```sh
  npm install express
  ```
  ```sh
  npm install @types/express -D
  ```
  
3. Install NPM Cors packages 
  
  ```sh
  npm install cors
  ```
  ```sh
  npm install @types/cors -D
  ```
  
4. Install NPM Node packages 
  
  ```sh
  npm install ts-node-dev -D
  ```
5. Run NPM developer

  ```sh
  npm run dev
   ```
## Uso

Uma API onde pode ser criado um site de ecommerce, com usuário, produtos e compras. 

## Contato

Manassés Almeida  - manasses2@gmail.com

Project Link: (https://github.com/manassesdev2)
<br/>

[![Linkedin](https://img.shields.io/badge/linkedin-%230A66C2.svg?&style=for-the-badge&logo=linkedin&logoColor=white&link=https://www.linkedin.com/in/andrejaques/)](https://www.linkedin.com/in/devmanasses/)

## Agradecimentos

* A DEUS por me proporcionar todos os recursos necessários para o projeto
* Aos professores da Labenu e aos colegas que me ajudaram no decorrer do projeto
* Minha esposa e meus familiares pelo apoio ao longo da construção do projeto
