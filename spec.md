# Specify — Cadastro e listagem de produtos

## Objetivo
Nesta iteração, será desenvolvida a funcionalidade de cadastro e listagem de produtos do sistema Controle de Estoque.

## Comportamento esperado
- O usuário poderá cadastrar um produto informando nome, quantidade e preço.
- O sistema deverá verificar se o nome foi preenchido.
- A quantidade deverá ser um número inteiro igual ou maior que zero.
- O preço deverá ser um número igual ou maior que zero.
- Depois do cadastro, o produto deverá ser salvo no banco de dados SQLite.
- O sistema deverá permitir consultar e visualizar os produtos cadastrados.
- Os dados deverão continuar disponíveis depois que o programa for fechado e aberto novamente.

## Restrições
- O projeto continuará utilizando Python e SQLite.
- Não utilizar arquivos JSON para armazenar os produtos.
- Não apagar nem recriar o banco de dados automaticamente.
- Não incluir funcionalidades que não façam parte deste recorte.

## Critérios para considerar pronto
- É possível cadastrar um produto com dados válidos.
- O sistema impede o cadastro com nome vazio, quantidade negativa ou preço negativo.
- Os produtos cadastrados ficam gravados no SQLite.
- É possível listar os produtos salvos.
- Os dados continuam disponíveis após reiniciar o programa.

## Fora do escopo
Nesta iteração não serão implementados edição e exclusão de produtos, controle de entrada e saída de estoque, relatórios, usuários ou integração com leitor de código de barras.
