# Governança

Este documento define a governança mínima do repositório institucional para turmas de Projeto Integrador no GitHub Enterprise `Campus-CEUB`.

## Papéis

- Professor: define os critérios avaliativos, acompanha as `milestones` e valida as entregas.
- Equipe: organiza o backlog, executa a sprint e preserva a rastreabilidade.
- Responsável pela issue: conduz a entrega, atualiza o status e organiza as evidências.
- Reviewer: analisa o `pull request`, registra comentários e confirma a aderência ao combinado.

## Fluxo de trabalho

1. Registrar a demanda em uma `issue`.
2. Criar uma `branch` vinculada a essa `issue`.
3. Executar o trabalho em commits pequenos e coerentes.
4. Abrir um `pull request` com contexto, validação e evidências.
5. Realizar a `review` antes do `merge`.
6. Integrar à `main` somente após a aprovação.
7. Registrar a conclusão e as evidências no relatório da sprint.

## Definition of Ready

Uma `issue` está pronta para desenvolvimento quando possui descrição clara, critérios de aceite verificáveis, prioridade definida, responsável nomeado ou apta para atribuição, `milestone` ou sprint prevista e dependências conhecidas.

## Definition of Done

Uma entrega só é considerada concluída quando a `issue` está vinculada e fechada, existe um `pull request` revisado e aprovado, a evidência foi registrada, a documentação foi atualizada quando necessário, um ADR foi criado quando a decisão alterou escopo, processo, arquitetura, integração, critério avaliativo ou outro ponto que precise de histórico consultável, e o relatório da sprint foi atualizado quando a entrega fizer parte da avaliação.

## Política de branches

- A `main` deve permanecer protegida e sem commit direto.
- Use nomes como `feature/<issue>-descricao`, `docs/<issue>-descricao` ou `fix/<issue>-descricao`.
- As branches `develop` e `release/sprint-XX` são opcionais e ficam a critério da disciplina.
- Cada `branch` deve tratar um recorte claro de trabalho, para facilitar a `review` e o `merge`.

## Reviews

- Todo `pull request` deve solicitar ao menos uma `review` antes do `merge`.
- Os comentários precisam ser respondidos no próprio `pull request`, para manter a trilha técnica.
- A `review` deve verificar critério de aceite, risco, evidências e impacto nos documentos.

## Evidências

As evidências aceitas incluem links para `issues`, `pull requests`, commits, relatórios de sprint, atas, protótipos, registros de validação, capturas de tela e documentos revisados.

## Tratamento de riscos e erros de processo

- Trabalho sem `issue`: interromper a execução, registrar a demanda e reenquadrar a atividade antes de continuar.
- Commit direto na `main`: abrir um registro do erro, corrigir o fluxo e reforçar a proteção da branch.
- Falta de participação rastreável: redistribuir a responsabilidade e exigir evidências individuais no repositório.
- Sprint sem entrega concluída: registrar os impedimentos, revisar o escopo e renegociar a prioridade com o professor e a equipe.
- Credenciais expostas: remover o segredo, rotacionar o acesso, registrar o incidente e documentar a ação corretiva.
