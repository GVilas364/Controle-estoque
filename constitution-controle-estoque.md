# Constitution — Controle de Estoque

## 1. Objetivo do projeto

O Controle de Estoque é uma aplicação simples para pequenas empresas, com o objetivo de organizar produtos e acompanhar as quantidades disponíveis. O projeto será desenvolvido gradualmente usando Python e JSON para armazenamento inicial dos dados.

## 2. Papéis e responsabilidades

- **Aprovação da spec:** os dois integrantes da dupla devem revisar e aprovar a especificação e os critérios de aceitação antes do início de cada funcionalidade.
- **Aprovação do merge:** um integrante revisa as alterações feitas pelo outro antes do merge. Quando a alteração for feita com apoio de um agente de IA, pelo menos um integrante deve revisar e aprovar antes de incorporá-la à branch principal.
- **Responsabilidade dos integrantes:** a dupla decide os requisitos, prioridades, regras de funcionamento e se uma funcionalidade atende ao que foi combinado.
- **Responsabilidade do agente de IA:** o agente pode sugerir soluções, implementar tarefas aprovadas, criar ou atualizar testes e documentação e preparar alterações em uma branch de trabalho. Ele não pode aprovar o próprio trabalho nem fazer merge sozinho na branch principal.

## 3. O que o agente pode versionar sem aprovação prévia

Depois que a tarefa estiver definida e aprovada na spec, o agente pode criar ou modificar, em uma branch de trabalho:
- funções e módulos Python relacionados às funcionalidades aprovadas;
- telas ou componentes simples da aplicação, caso sejam adicionados ao projeto;
- leitura, gravação e organização dos dados em JSON;
- testes e documentação técnica;
- correções de erros que não alterem os requisitos ou o comportamento combinado.

O agente precisa pedir autorização antes de:
- mudar os requisitos ou critérios de aceitação;
- alterar a estrutura ou o formato dos dados JSON de maneira incompatível;
- adicionar banco de dados, serviços externos ou dependências que mudem significativamente a solução;
- mudar regras de cadastro, preço ou atualização de quantidade;
- excluir dados, arquivos ou funcionalidades existentes.

## 4. Regras inegociáveis

1. **Integridade dos dados:** operações de cadastro e atualização não podem apagar ou modificar outros produtos indevidamente. A gravação e a leitura do arquivo JSON devem preservar os dados cadastrados.
2. **Aprovação humana dos requisitos:** o agente de IA não pode inventar, remover ou alterar funcionalidades e critérios de aceitação sem aprovação dos dois integrantes da dupla.
3. **Revisão antes do merge:** nenhuma alteração feita pelo agente pode ser incorporada à branch principal sem que pelo menos um integrante revise o código e verifique se ele corresponde à tarefa aprovada.
4. **Validação das informações:** o sistema deve validar os dados de produtos, como nome, quantidade e preço, antes de cadastrá-los ou atualizá-los. As regras específicas de validação devem seguir a spec aprovada.
5. **Proteção do projeto:** o agente não pode excluir arquivos ou dados cadastrados nem substituir o conteúdo do arquivo JSON sem autorização explícita da dupla.

## 5. Critérios para considerar uma funcionalidade pronta

Uma funcionalidade só será considerada concluída quando:
- atender ao que foi definido na spec aprovada;
- funcionar nos cenários previstos, incluindo situações de entrada inválida quando aplicável;
- preservar corretamente os dados dos produtos no arquivo JSON;
- não causar erros nas funcionalidades já existentes;
- tiver sido revisada por pelo menos um integrante da dupla.

## 6. Autoridade final

As decisões sobre requisitos, prioridades, regras de negócio, formato dos dados e aceitação das funcionalidades pertencem aos dois integrantes da dupla. O agente de IA é uma ferramenta de apoio e deve seguir esta Constitution.
