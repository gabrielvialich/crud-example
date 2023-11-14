# CRUD em NodeJS com NestJS - Exemplo Educacional

Este é um projeto CRUD desenvolvido em NodeJS utilizando o framework NestJS, inicialmente criado com o CLI do NestJS através do comando `npx @nestjs/cli new crud-example`. O principal objetivo deste projeto é fornecer uma plataforma para aprender as características e funcionalidades do NestJS, com a implementação prática de um CRUD.

## Créditos

Este projeto foi inspirado na ideia original do CRUD, que é creditada a [Luiz Duarte](https://github.com/luiztools). Agradecemos ao Luiz Duarte por sua contribuição para o desenvolvimento do conceito CRUD.

## Como Utilizar o Projeto

1. **Instalação de Dependências**: Execute `npm install` para instalar as dependências necessárias.

2. **Execução do Servidor**: Utilize `npm run start` para iniciar o servidor NestJS.

3. **Endpoints API**:

   - **Adicionar Usuário (POST)**: `POST http://localhost/users`
     - Exemplo de corpo da solicitação (JSON):
       ```json
       {
         "name": "Nome do Usuário",
         "age": 25,
         "uf": "SP"
       }
       ```

   - **Listar Usuários (GET)**: `GET http://localhost/users`

   - **Obter Usuário por ID (GET)**: `GET http://localhost/users/:id`
     - Substitua `:id` pelo ID do usuário desejado.

   - **Deletar Usuário por ID (DELETE)**: `DELETE http://localhost/users/:id`
     - Substitua `:id` pelo ID do usuário a ser removido.

   - **Substituir Usuário por ID (PUT)**: `PUT http://localhost/users/:id`
     - Substitua `:id` pelo ID do usuário a ser substituído.
     - Exemplo de corpo da solicitação (JSON):
       ```json
       {
         "name": "Novo Nome",
         "age": 30,
         "uf": "RJ"
       }
       ```

   - **Atualizar Característica do Usuário por ID (PATCH)**: `PATCH http://localhost/users/:id`
     - Substitua `:id` pelo ID do usuário a ser atualizado.
     - Exemplo de corpo da solicitação (JSON):
       ```json
       {
         "age": 26
       }
       ```

4. **Testando com o Postman**: Utilize o Postman ou outra ferramenta similar para testar os endpoints conforme descrito acima.

## Contribuições e Feedback

Este projeto é destinado principalmente ao aprendizado do NestJS. Sinta-se à vontade para contribuir com melhorias, experimentar diferentes funcionalidades do NestJS ou reportar problemas que encontrar durante a exploração deste exemplo educacional.

Lembre-se de que o objetivo principal é a experiência de aprendizado, então divirta-se explorando o NestJS!