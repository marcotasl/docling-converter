# Regras de Trabalho - Docling Project

## Regra Fundamental

- **Nunca avance para a próxima etapa (task, subtask ou fase) sem antes concluir e testar completamente a etapa anterior.**
  - A conclusão deve ser registrada no `tasks.md` e no dashboard.
  - O teste deve ser documentado, mesmo que seja manual.
  - Só após validação e revisão, a próxima etapa pode ser iniciada.

## 1. Gestão de Status das Tasks

### 1.1 Atualização de Status
- **Início da Task**:
  - Atualizar o status da task para "Em Progresso" em:
    - Arquivo `tasks.md`
    - Dashboard (`tasks-dashboard.html`)
  - Registrar a data de início
  - Atualizar o progresso geral no dashboard

- **Conclusão da Task**:
  - Atualizar o status da task para "Concluído" em:
    - Arquivo `tasks.md`
    - Dashboard (`tasks-dashboard.html`)
  - Registrar a data de conclusão
  - Atualizar o progresso geral no dashboard
  - Atualizar as subtasks relacionadas

### 1.2 Formato de Atualização
```markdown
## [Nome da Task]
- Status: [Pendente/Em Progresso/Concluído]
- Data Início: [DD/MM/YYYY]
- Data Conclusão: [DD/MM/YYYY]
- Progresso: [0-100%]
```

### 1.3 Checklist de Atualização
- [ ] Atualizar status no `tasks.md`
- [ ] Atualizar status no dashboard
- [ ] Atualizar datas
- [ ] Atualizar progresso
- [ ] Atualizar subtasks
- [ ] Verificar consistência entre arquivos

## 2. Ordem de Trabalho

### 2.1 Priorização
1. Tasks com dependências concluídas
2. Tasks de menor complexidade
3. Tasks de maior impacto

### 2.2 Fluxo de Trabalho
1. Verificar dependências
2. Atualizar status para "Em Progresso"
3. Desenvolver task
4. Testar implementação
5. Atualizar status para "Concluído"
6. Verificar impacto em tasks dependentes

## 3. Documentação

### 3.1 Atualização de Documentos
- Manter `tasks.md` e dashboard sincronizados
- Documentar decisões técnicas
- Registrar problemas encontrados
- Documentar soluções implementadas

### 3.2 Formato de Documentação
```markdown
## [Nome da Task]
### Decisões Técnicas
- [Decisão 1]
- [Decisão 2]

### Problemas Encontrados
- [Problema 1]
  - Solução: [Descrição da solução]

### Aprendizados
- [Aprendizado 1]
- [Aprendizado 2]
```

## 4. Controle de Versão

### 4.1 Commits
- Commits específicos para atualizações de status
- Mensagens claras e descritivas
- Referência ao número da task

### 4.2 Formato de Commit

## 5. Revisão

### 5.1 Checklist de Revisão
- [ ] Status atualizado em todos os arquivos
- [ ] Documentação atualizada
- [ ] Código testado
- [ ] Commits realizados
- [ ] Impacto em outras tasks verificado

### 5.2 Validação
- Verificar consistência entre arquivos
- Validar progresso geral
- Confirmar atualização de dependências
- Verificar documentação

## 6. Exceções

### 6.1 Situações Especiais
- Tasks bloqueadas
- Mudanças de escopo
- Problemas técnicos
- Dependências externas

### 6.2 Procedimento para Exceções
1. Documentar a situação
2. Atualizar status para "Bloqueado" se necessário
3. Notificar equipe
4. Buscar resolução
5. Atualizar documentação

## 7. Manutenção

### 7.1 Atualizações Periódicas
- Revisar status das tasks diariamente
- Atualizar progresso semanalmente
- Validar dependências mensalmente

### 7.2 Limpeza
- Remover tasks concluídas do dashboard ativo
- Arquivar documentação antiga
- Manter histórico de alterações

## 8. Comunicação

### 8.1 Notificações
- Informar equipe sobre mudanças de status
- Notificar sobre bloqueios
- Compartilhar progresso

### 8.2 Canais
- Issues do GitHub
- Pull Requests
- Documentação do projeto
- Dashboard

## 9. Métricas

### 9.1 Acompanhamento
- Velocidade de conclusão
- Qualidade do código
- Cobertura de testes
- Satisfação do usuário

### 9.2 Relatórios
- Status semanal
- Progresso mensal
- Retrospectiva trimestral
