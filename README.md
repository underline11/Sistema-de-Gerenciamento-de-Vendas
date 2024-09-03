Este projeto consiste na criação de um sistema de vendas utilizando SQL para a criação de banco de dados, tabelas, inserção de dados, consultas, atualizações e exclusões. O sistema gerencia informações de produtos, clientes e vendas, permitindo realizar operações básicas de uma aplicação de vendas.

Objetivos:

Criar um banco de dados chamado SistemaVendas.
Criar tabelas para armazenar informações sobre produtos, clientes e vendas.
Inserir dados de exemplo nas tabelas.
Realizar operações CRUD (Create, Read, Update, Delete) no banco de dados.
Executar consultas SQL para visualizar as informações de forma estruturada.
# Sistema de Vendas Simples

## Descrição
Este projeto implementa um sistema de vendas básico utilizando SQL. O sistema é composto por três tabelas principais: `Produtos`, `Clientes` e `Vendas`. Através dessas tabelas, é possível gerenciar as informações relacionadas aos produtos disponíveis, clientes cadastrados e vendas realizadas.

## Estrutura do Banco de Dados
- **Produtos:** Armazena informações sobre os produtos, incluindo nome, preço e quantidade em estoque.
- **Clientes:** Armazena informações sobre os clientes, como nome, email e telefone.
- **Vendas:** Armazena informações sobre as vendas realizadas, incluindo o produto vendido, o cliente, a quantidade vendida e a data da venda.

## Funcionalidades
1. **Criação do Banco de Dados e Tabelas:** 
   - Criação do banco de dados `SistemaVendas`.
   - Criação das tabelas `Produtos`, `Clientes` e `Vendas`.

2. **Inserção de Dados:**
   - Inserção de registros nas tabelas `Produtos` e `Clientes`.
   - Registro de vendas na tabela `Vendas`.

3. **Consultas (SELECT):**
   - Consultas básicas para listar todas as vendas.
   - Consultas para listar vendas com detalhes do cliente e produto.

4. **Atualização de Dados (UPDATE):**
   - Atualização do preço de um produto.
   - Atualização do email de um cliente.

5. **Exclusão de Dados (DELETE):**
   - Exclusão de vendas e produtos do banco de dados.

6. **Junções (JOIN):**
   - Consultas utilizando junções para exibir informações detalhadas sobre as vendas.

## Como Usar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/sistema-vendas-simples.git
Importe o script SQL em seu servidor de banco de dados.

Execute as consultas para criar o banco de dados, tabelas e inserir os dados.

Utilize as consultas disponíveis para explorar os dados e realizar operações de atualização e exclusão.

Estrutura do Projeto
database.sql: Script SQL contendo todas as instruções para a criação do banco de dados e tabelas, além de exemplos de inserção e consultas.
Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.
