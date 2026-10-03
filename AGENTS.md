# BonCourageTech - instruções de contribuição

## Autorização de agentes para branches e PRs

- Allef autorizou em 03/10/2026 todos os agentes e IAs atuais e futuros designados por ele ou por colaboradores autorizados a implementar tarefas, criar commits, fazer push nas branches de trabalho e abrir/atualizar PRs nos repositórios BonCourageTech. Dentro do escopo autorizado do ticket, prossiga sem pedir confirmação de rotina para cada commit, push ou PR.
- Use a identidade ou integração autenticada que já tenha permissão de escrita no repositório. Confirme o destino corporativo antes do push. A autorização não cria contas, credenciais nem permissões técnicas para apps futuros; novas integrações precisam de onboarding próprio.
- Trabalhe em branch dedicada com a chave do Jira. Preserve alterações de outros colaboradores. Não faça force push nem use esta autorização como permissão de push direto em main/master/default, merge ou deploy. As regras específicas de revisão/merge e Jenkins continuam aplicáveis.
- Após publicar a branch/PR, conclua os testes proporcionais ao risco, registre SHA/PR/resultados reais no Jira e deixe a entrega pronta para revisão. Commit, push e build não comprovam publicação nem funcionamento do ambiente.
- Quando o Jira estiver indisponível, salve a atualização sanitizada pendente e informe o bloqueio. A indisponibilidade não impede preparar e publicar o commit/PR autorizado; sincronize o registro assim que voltar e regularize-o antes de merge/entrega final.
- Para a publicação de código, testes e documentação sanitizados que não manipulem valores reais, a ausência de uma skill de segredos não deve bloquear o commit/PR. Leitura, escrita e rotação de credenciais reais continuam sujeitas ao fluxo seguro específico; nunca recupere valores para colocá-los em contexto ou no Git.
- Gabriel pode usar seu agente neste fluxo. Cada colaborador é responsável por revisar a contribuição da IA e acompanhar a tarefa até a validação da entrega.
- Novos repositórios devem receber estas instruções e as pontes Claude/Copilot no onboarding. Um AGENTS.md no repositório .github não é herdado automaticamente por outros repositórios.
- Referências: [KAN-25](https://boncouragetech.atlassian.net/browse/KAN-25) e [governança](https://boncouragetech.atlassian.net/wiki/spaces/COBALT/pages/688166).

Leia o ticket Jira e os documentos vinculados antes do trabalho. Use a chave KAN em branch, commits e PR. Atualize o Jira após cada avanço, com SHA, links, validação real e limitações. Não exponha segredos ou dados reais de clientes. Deploy de aplicações somente pelo Jenkins e orçamento AWS até USD 225/mês. Elias conduz Discovery; Gabriel implementa; Allef valida escopo e aprova código. Preserve as regras de revisão e histórico. Esta política não concede bypass aos agentes.
