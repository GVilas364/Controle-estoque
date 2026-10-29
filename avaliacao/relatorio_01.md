# Relatório — Controle de Estoque

## Viabilidade

- Grupo: Dupla 03
- Integrantes: Mariano de Souza Negrão e Guilherme Vilas Boas Fagundes.
- Repositório: https://github.com/GVilas364/Controle-estoque
- Stack: Python, arquivos JSON e Visual Studio Code.
- Veredito: Viável

O problema já está no tamanho da etapa: uma pessoa de uma empresa pequena cadastra um produto, vê a lista e atualiza a quantidade. Python e JSON dispensam banco nesta etapa. Eu havia comentado que seria melhor usar um banco , mas se preferirem podem criar apenas a coleção de JSON e ler com o Python, escolha de vocês. 

## SWOT

### Forças

Problema, usuário e três operações estão em um parágrafo. Python e JSON são um processo só, sem banco para instalar. 

### Fraquezas

O PDF não diz o que acontece com quantidade negativa, nome repetido ou nome vazio. O preço aparece no README e não nas operações do PDF. 

### Oportunidades

Constitution com nome e quantidade do produto, e as três operações: cadastrar, listar e atualizar. O preço entra só se continuar na spec. Um arquivo JSON guarda a lista.

### Ameaças

Banco, login e relatórios antes de as três operações existirem. 

## Stack técnica

**Parecer: Adequada.** Python com arquivo JSON serve às três operações; banco de dados não entra nesta etapa.

Python alcança cadastrar, listar e atualizar quantidade. O JSON guarda a lista no disco e dispensa servidor. Visual Studio Code é o ambiente, e a inteligência artificial entra como apoio ao desenvolvimento, como o README já diz, e não como componente do produto. Não há motivo para trocar a linguagem nem para antecipar um banco.

O preço, se a dupla o mantiver, é mais um campo no mesmo JSON: nome, quantidade e preço. A spec precisa dizer o que recusar: quantidade negativa, nome vazio e dois produtos com o mesmo nome. SQLite só depois que essas três operações estiverem especificadas e funcionando.

## Recomendação

**Especifiquem nome e quantidade, com cadastrar, listar e atualizar.**

O Controle de Estoque já está no tamanho da disciplina. A constitution registra o produto com nome e quantidade. A pessoa cadastra, vê a lista e corrige a quantidade. O preço fica se a dupla quiser o campo que o README já citou; se ficar, entra na mesma spec. A operação recusa nome vazio, quantidade negativa e nome repetido. O JSON é o único armazenamento. Banco, login e relatórios esperam esse fluxo. O próximo texto visível é essa constitution.
