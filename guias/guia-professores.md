# Guia dos professores

## Objetivo

Este guia orienta os professores a usar o template institucional em disciplinas de Projeto Integrador na organização do GitHub Enterprise `Campus-CEUB`.

## Criação do repositório

1. Crie um repositório a partir do [TEMPLATE-repositorio-projeto-integrador](https://github.com/CAMPUSCEUB/TEMPLATE-repositorio-projeto-integrador).
2. Use um nome do projeto que representa o sistema ou ativo de TI que será gerado e que tenha sido aprovado no subsistema de portfólio de TI. (ex. **SisControleVendas**)
3. Defina a visibilidade conforme a política institucional da Cátedra de Projetos de TI.
4. Convide os alunos com a permissão adequada.
5. Configure as `milestones`, as labels, o GitHub `Project` e a proteção da `main`.
6. Antes de publicar ou reutilizar o repositório fora da turma, revise o arquivo `LICENSE` e substitua o placeholder por uma licença efetiva.

## Configuração da turma

Ao iniciar a turma, configure o repositório como espaço oficial da disciplina, revise o material base do template e alinhe com os estudantes como `issues`, `branches`, `pull requests` e relatórios de sprint serão usados ao longo do semestre.

## Equipes

Organize os alunos em times conforme a estratégia da disciplina. Os times podem representar grupos fixos de projeto ou apenas facilitar a administração de acesso, o acompanhamento e a distribuição de responsabilidade dentro do GitHub Enterprise.
    
## Permissões

Conceda aos alunos apenas as permissões necessárias para colaborar no repositório, mantendo a governança institucional sobre a `main`, os artefatos avaliativos e as configurações principais do projeto.

## Configuração do Project
1. Crie um Project partir do template institucional.
2. Use um nome padronizado contendo o ano, o semestre de criação, a sigla do curso, a sigla de PI ou PF e o nome do Project (ex. 261-CC-PI-II-nome do project)
3. Vincule o Project ao repositório correspondente 

## Cadência sugerida da sprint

* 1 semana: acompanhamento intenso e entregas pequenas.
* 2 semanas: recomendação equilibrada para a maioria das turmas.
* 4 semanas: adequada para projetos com maior carga de pesquisa ou menor frequência de encontros.

## Marcos

Crie `milestones` por sprint ou marco avaliativo para organizar o backlog, tornar os prazos visíveis e consolidar o acompanhamento das entregas previstas em cada etapa da disciplina. 

Exemplos de marcos: (imagine uma sprint de 14 dias)
* Infraestrutura pronta: O ambiente de homologação está configurado e acessível no dia 3.
* Design aprovado: Os protótipos de alta fidelidade da tela de login foram validados pelo cliente no dia 4.
* Testes de segurança: A varredura inicial de vulnerabilidades do novo módulo foi concluída no dia 8.
* Critério de aceite atingido: Todas as histórias de usuário da Sprint Goal passaram com sucesso no ambiente de teste.
 
## Quadro do projeto

Mantenha um GitHub `Project` para acompanhar o fluxo das `issues` da turma. O quadro deve permitir visualizar o backlog, os itens em andamento, as pendências de revisão e as entregas concluídas.

## Trabalhando com Issues

A `issue`, pertence a um repositório repositório e representa um bug a ser consertado, uma melhoria no sistema, uma documentação ou a necessidade de uma pesquisa.

A `issue` que possui o `Label` igual a `enhacement`, ao ser incluída em um `project`, deve ser classificadas com `Type` correspondente: `epic`, `feature`, `PBI` ou `task`.

Para facilitar, pense em uma EAP (Estrutura Analítica do Projeto).   O sistema é desdobrado em módulos, cada módulo desdobrado em funcionalidades. No `CAMPUSCEUB` temos o Projeto de Exemplo [FoodNow](https://github.com/orgs/CAMPUSCEUB/projects/16)

Como organizar então as Issues que representam os requisitos de um sistema?

1. Estimule os alunos a dividir o sistema em módulos.  Por exemplo: o módulo de "Contas a Pagar".
2. Para cada módulo, peça para o aluno criar uma `issue` do Tipo "epic".
3. Peça para os alunos dividirem os módulos em grandes funcionalidades. No caso do "Contas a Pagar", seriam por exemplo: "Cadastro de Fornecedores", "Agendamento de Boletos", "Conciliação Bancária" e "Alertas de vencimento"
4. Crie sub-issues aos `epic` uma `issue` do tipo `feature` para cada funcionalidade.
5. Peça aos alunos para localizarem o `Project` correspondente ao Repositório do sistema.
6. Para cada `issue` do tipo `feature`, peça aos alunos para pensarem em User Story que consigam ser desenvolvidas dentro de uma Sprint.
7. Para cada User Story, peça para que cadastrem uma `issue` do tipo `PBI`
8. Para cada `issue` do tipo `PBI`, peça para que o aluno planeje as tarefas que serão necessárias de executar para entregar o `PBI`. 
9. Para cada tarefa, cadastre uma subissue do tipo `task`. Lembre-se de que as tarefas devem estar com o verbo no infinitivo e que tenham alocação apenas para um aluno! Evite grupos em tarefas para não perder a rastreabilidade de quem fez o quê.

## Acompanhamento

Use `issues`, `pull requests`, commits, `reviews`, `milestones`, relatórios de sprint e entregas como evidências de evolução e participação.

## Avaliação

A rubrica sugerida está em [rubrica-avaliacao.md](rubrica-avaliacao.md). O professor pode adaptar os pesos e os critérios conforme o plano de ensino.

## Integração contínua (opcional)

Se a disciplina quiser aproximar os alunos de práticas de mercado, é possível adicionar um fluxo leve de integração contínua independente de stack, como verificação de Markdown ou de links. Trate esse recurso como opcional, para não tornar o processo pesado em disciplinas iniciais.

## Operação da turma

Durante a operação da disciplina, acompanhe a abertura e o fechamento de `issues`, solicite a atualização do quadro e das `milestones`, estimule as revisões entre pares quando fizer sentido pedagógico e use os registros do repositório como base para feedback e avaliação contínua.
