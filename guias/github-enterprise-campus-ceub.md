# GitHub Enterprise Campus-CEUB

## Checklist inicial

- Criar o repositório a partir do template institucional.
- Confirmar a organização `Campus-CEUB`.
- Definir a visibilidade do repositório.
- Revisar o arquivo `LICENSE` e substituir o placeholder por uma licença efetiva antes de usar ou publicar o repositório da turma.
- Adicionar o professor como administrador ou mantenedor.
- Adicionar os estudantes com permissão de colaboração.
- Criar o GitHub `Project`.
- Criar as `milestones` das sprints.
- Criar as labels institucionais.
- Proteger a branch `main`.

## Labels institucionais sugeridas

- `enhancement` , que represeta um requisito ou nova característica
- `bug`, que representa um defeito
- `documentation`, que representa a documentação de suporte
- `research`, que representa uma pesquisa ou estudo prévio a ser realizado
As lables já foram criadas no Project vinculado ao repositório, mas se não foram certifique-se de criá-las 

Mantenha esses nomes exatos para preservar a compatibilidade com os forms de `issue`. Crie labels adicionais somente quando a turma precisar.

## Branch protection recomendada

- Exigir `pull request` antes do `merge`.
- Exigir ao menos uma aprovação, quando aplicável.
- Exigir conversas resolvidas antes do `merge`, quando disponível.
- Bloquear `force push` na `main`.

## Campos recomendados do Project

- `Status`: `Backlog`, `Ready`, `In Progress`, `Review`, `Done`.
- `Sprint`: sprint ou `milestone` correspondente.
- `Responsável`: aluno, dupla ou grupo.
- `Prioridade`: `Alta`, `Média`, `Baixa`.
- `Label`: as mesmas geradas na criação da Issue que são `enhancement`, `bug`, `documentation` e `research`
- `Tipo`: `Epic`, `Feature`, `PBI` (Product Backlog Item / User Story), `Task`,  em conformidade com o modelo SCRUM .
- `Bloqueado`: indicador de impedimento.

## Fonte de verdade dos campos

Para evitar divergência de dados, adote uma fonte única por informação:

- `Label`: definido pela `label` aplicada automaticamente pelo form de criação de uma `issue` (`tipo: enhacement`, `tipo: bug`, `tipo: documentation`, `tipo: researcha`). O campo `Tipo` do `Project` apenas espelha essa label para se planejar as Sprints com epics, features, PBI e tasks.
- `Prioridade`: definida no campo de prioridade da `issue` no momento da criação. O campo `Prioridade` do `Project` apenas espelha esse valor.

Não duplique a mesma informação em label e em campo ao mesmo tempo, para não criar registros conflitantes.
