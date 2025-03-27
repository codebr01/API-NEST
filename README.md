# API de Gerenciamento de Estoque

Este projeto é uma API desenvolvida com o framework **NestJS** para gerenciar o estoque de produtos. A API oferece funcionalidades de autenticação e gerenciamento de produtos, como cadastro, atualização, exclusão e listagem de produtos. Ela também suporta a autenticação de usuários com JWT (JSON Web Tokens) e conecta-se a um banco de dados MongoDB.

## Funcionalidades

- **Autenticação de Usuários**: Login com JWT, protegendo as rotas que exigem autenticação.
- **Cadastro de Produtos**: Permite adicionar novos produtos ao estoque.
- **Listagem de Produtos**: Recupera a lista de produtos do estoque.
- **Atualização de Produtos**: Modifica as informações de um produto existente.
- **Exclusão de Produtos**: Remove um produto do estoque.
- **Visualização de Detalhes do Produto**: Permite consultar informações detalhadas de um produto.
- **Gerenciamento de Categorias de Produtos**: Cadastra e lista as categorias dos produtos.
- **Estoque**: Atualiza a quantidade de um produto no estoque.

## Tecnologias Utilizadas

- **NestJS**: Framework para desenvolvimento da API.
- **MongoDB**: Banco de dados NoSQL para armazenamento dos dados.
- **JWT (JSON Web Tokens)**: Sistema de autenticação e autorização.
- **BcryptJS**: Biblioteca para criptografia de senhas.
- **Dotenv**: Carregamento de variáveis de ambiente.
