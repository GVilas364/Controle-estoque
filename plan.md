# Plan — Cadastro e listagem de produtos

## Stack
- Linguagem: Python.
- Banco de dados: SQLite.

## Etapas de implementação
1. Conferir a estrutura atual do projeto e como a conexão com o SQLite está organizada.
2. Criar ou ajustar a estrutura da tabela de produtos, sem apagar dados existentes.
3. Implementar a função responsável por cadastrar produtos no banco.
4. Validar nome, quantidade e preço antes de salvar.
5. Implementar a consulta que busca os produtos cadastrados.
6. Integrar o cadastro e a listagem ao fluxo atual do sistema.
7. Testar o cadastro, as validações, a listagem e a persistência dos dados.

## Pontos de atenção e riscos
- Preservar os registros que já existem no banco SQLite.
- Evitar criar tabelas duplicadas ou alterar a estrutura do banco de forma incompatível.
- Tratar entradas inválidas para que não sejam gravadas.
- Conferir se os dados continuam disponíveis depois de fechar e abrir o programa.
- Revisar as alterações em dupla antes de integrar à branch principal.

## Relação com o Specify
O plano implementa somente o cadastro e a listagem de produtos descritos na especificação. Edição, exclusão e outras funções ficam para iterações futuras.
