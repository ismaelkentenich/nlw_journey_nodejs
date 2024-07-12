# plann.er: Planejador de Viagens entre Amigos

## Descrição do Projeto
O **plann.er** é uma aplicação para planejamento de viagens entre amigos, desenvolvida em Node.js com TypeScript durante o evento NLW Journey da Rocketseat realizada em julho de 2024.

Permite aos usuários criar e gerenciar viagens de forma colaborativa, facilitando o compartilhamento de informações entre os participantes.

## Tecnologias Utilizadas
- **TypeScript**: Linguagem de programação para desenvolvimento mais seguro e escalável.
- **Fastify**: Framework web leve e eficiente para construção de APIs rápidas e escaláveis.
- **Prisma ORM**: ORM (Object-Relational Mapping) moderno para interação com banco de dados, com integração SQLite para persistência de dados.
- **Zod**: Biblioteca para validação de dados, garantindo a integridade e consistência das informações manipuladas na aplicação.

## Configuração do Ambiente
Para configurar e executar o projeto localmente, siga as instruções abaixo:

1. **Instalação das Dependências**

- npm install


2. **Configuração do Banco de Dados**
- O projeto utiliza SQLite como banco de dados. Certifique-se de ter o SQLite instalado localmente.
- O arquivo de banco de dados será criado automaticamente ao iniciar a aplicação.

3. **Variáveis de Ambiente**
- Crie um arquivo `.env` na raiz do projeto com as seguintes variáveis:
  ```
  DATABASE_URL="file:./dev.db"
  API_BASE_URL="http://localhost:3333"
  WEB_BASE_URL="http://localhost:3000"
  PORT="3333"
  ```
- Ajuste as URLs conforme necessário para o seu ambiente local.

4. **Execução do Projeto**

- npm run dev


## Utilização do Prisma
Este projeto utiliza o Prisma como ORM para interação com o banco de dados SQLite. O Prisma fornece uma maneira fácil e segura de se comunicar com o banco de dados.

### Configuração do Prisma
1. Inicialize o Prisma com SQLite como provedor de dados:

- npx prisma init --datasource-provider SQLite

2. Execute a migração do Prisma para criar as tabelas no banco de dados dev.db

- npx prisma migrate dev

3. Inicie o Prisma Studio para visualizar e interagir com seus dados:

- npx prisma studio

## Referência
 - [NLW Journey](https://www.rocketseat.com.br/eventos/nlw)
 - [RocketSeat](https://www.rocketseat.com.br/)
 - [NodeJs](https://nodejs.org/pt/download/package-manager/)
 - [Fastify Type Provider Zod](https://github.com/turkerdev/fastify-type-provider-zod)
 - [Postman](https://www.postman.com/)
 - [Nodemailer](https://nodemailer.com/)
 - [HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)

## Autores
- [@diego3g](https://github.com/diego3g)
- [@ismaelkentenich](https://github.com/ismaelkentenich)

