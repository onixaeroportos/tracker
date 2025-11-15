# Issue Templates - Guia de Referência

Este diretório contém templates para diferentes tipos de issues. Use este guia para escolher o template correto e aplicar as labels adequadas.

## Templates Disponíveis

### 1. Bug Report (`bug-report.md`)
**Quando usar:** Para reportar bugs ou problemas no sistema.

**Labels padrão:** `bug`

**Labels adicionais recomendadas:**
- `ui-bug` - Bug visual específico
- `config-error` - Problemas de configuração
- `build-issue` - Falha ao compilar
- `deployment-issue` - Problemas no deploy
- `slow-query` - Consultas lentas
- `memory-issue` - Problemas de memória
- `monitoring-alert` - Item originado de alertas
- `permissions` - Questões de acesso/ACL

**Uso:** Qualquer bug técnico ou funcional.

---

### 2. Feature Request (`feature-request.md`)
**Quando usar:** Para sugerir novas funcionalidades ou melhorias.

**Labels padrão:** `enhancement`

**Labels adicionais recomendadas:**
- `ux-improvement` - Melhorias na experiência
- `visual-polish` - Ajuste visual fino
- `ui-update` - Atualizações na interface
- `ux-research` - Requer pesquisa de UX
- `prototype` - Requer protótipo
- `scope-change` - Mudança no escopo
- `stakeholder-feedback` - Feedback de stakeholders
- `needs-approval` - Aguardando aprovação
- `breaking-change` - Alterações que quebram compatibilidade

**Uso:** Novas features, melhorias, mudanças de comportamento.

---

### 3. Task (`task.md`)
**Quando usar:** Para criar tarefas de trabalho ou atividades.

**Labels padrão:** `task`

**Labels adicionais recomendadas:**
- `chore` - Modificação simples
- `cleanup` - Limpeza de código
- `deprecated` - Algo obsoleto
- `refactor` - Refatoração
- `maintenance` - Manutenção
- `monitoring` - Logs, métricas, alertas
- `infra` - Infraestrutura
- `ci-update` - Mudanças no CI
- `environment` - Configuração de ambiente
- `planning` - Planejada para futuros ciclos
- `ready` - Pronto para desenvolvimento
- `analysis` - Em fase de análise

**Uso:** Tarefas gerais, chores, manutenção, refatoração.

---

### 4. Dependency (`dependency.md`)
**Quando usar:** Para gerenciar dependências do projeto.

**Labels padrão:** `dependency`

**Labels adicionais recomendadas:**
- `dependencies` - Dependências do projeto
- `version-update` - Atualização de versão
- `breaking-change` - Se a atualização quebra compatibilidade

**Uso:** Adicionar, atualizar, remover dependências.

---

### 5. Component (`component.md`)
**Quando usar:** Para criar ou modificar componentes.

**Labels padrão:** `component`

**Labels adicionais recomendadas:**
- `ui-update` - Atualização de componente UI
- `core` - Mudanças em componentes core
- `refactor` - Refatoração de componente

**Uso:** Criação, modificação, refatoração de componentes.

---

### 6. Design Bug (`design-bug.md`)
**Quando usar:** Para reportar problemas de design ou interface.

**Labels padrão:** `design`, `bug`, `ui-bug`

**Labels adicionais recomendadas:**
- `visual-polish` - Para ajustes finos
- `critical` - Se for crítico

**Uso:** Problemas visuais, de layout, responsividade, UI.

---

### 7. Doc Bug Report (`doc-bug-report.md`)
**Quando usar:** Para reportar erros na documentação.

**Labels padrão:** `documentation`, `bug`

**Labels adicionais recomendadas:**
- `api-docs` - Se for documentação de API
- `internal-docs` - Se for documentação interna

**Uso:** Erros, informações incorretas ou desatualizadas na docs.

---

### 8. Documentation Request (`documentation-request.md`)
**Quando usar:** Para solicitar nova documentação.

**Labels padrão:** `documentation`

**Labels adicionais recomendadas:**
- `api-docs` - Documentação de APIs
- `needs-examples` - Requer exemplos
- `internal-docs` - Documentação interna

**Uso:** Solicitar nova documentação ou melhorias na docs.

---

### 9. Architecture (`architecture.md`)
**Quando usar:** Para mudanças arquiteturais significativas.

**Labels padrão:** `architecture`

**Labels adicionais recomendadas:**
- `breaking-change` - Se quebrar compatibilidade
- `critical` - Se for crítica
- `needs-approval` - Requer aprovação
- `scope-change` - Mudança significativa

**Uso:** Mudanças arquiteturais, refatorações grandes, migrações.

---

### 10. Security Audit (`security-audit.md`)
**Quando usar:** Para solicitar auditorias de segurança.

**Labels padrão:** `security-audit`

**Labels adicionais recomendadas:**
- `critical` - Se for crítico
- `permissions` - Se for sobre ACL

**Uso:** Auditorias de segurança, revisões de código de segurança.

---

### 11. Vulnerability (`vulnerability.md`)
**Quando usar:** Para reportar vulnerabilidades de segurança.

**Labels padrão:** `vulnerability`, `security`

**Labels adicionais recomendadas:**
- `critical` - Sempre aplicar se for vulnerabilidade
- `do-not-merge` - Até ser resolvida

**Uso:** Vulnerabilidades encontradas, riscos de segurança.

---

### 12. Incident (`incident.md`)
**Quando usar:** Para registrar incidentes em produção.

**Labels padrão:** `incident`, `critical`

**Labels adicionais recomendadas:**
- `release-blocker` - Se bloquear release
- `monitoring-alert` - Se originado de alerta

**Uso:** Incidentes de produção, problemas críticos.

---

### 13. Customer Issue (`customer-issue.md`)
**Quando usar:** Para problemas reportados por clientes reais.

**Labels padrão:** `customer-issue`

**Labels adicionais recomendadas:**
- `bug` - Se for um bug
- `critical` - Se for crítico para o cliente
- `help-wanted` - Se precisar de atenção extra

**Uso:** Problemas reportados por clientes, tickets de suporte.

---

### 14. Technical Debt (`technical-debt.md`)
**Quando usar:** Para registrar dívida técnica.

**Labels padrão:** `technical-debt`

**Labels adicionais recomendadas:**
- `cleanup` - Para limpeza de código
- `refactor` - Para refatoração
- `deprecated` - Se for sobre código obsoleto
- `optimization` - Se for sobre performance

**Uso:** Código legado, melhorias necessárias, refatorações.

---

### 15. Optimization (`optimization.md`)
**Quando usar:** Para solicitar otimizações.

**Labels padrão:** `optimization`

**Labels adicionais recomendadas:**
- `slow-query` - Para otimizações de banco
- `memory-issue` - Para problemas de memória
- `performance` - Para performance geral

**Uso:** Otimizações de performance, consultas lentas, uso de memória.

---

### 16. API Documentation (`api-docs.md`)
**Quando usar:** Para documentação específica de APIs.

**Labels padrão:** `api-docs`, `documentation`

**Labels adicionais recomendadas:**
- `needs-examples` - Se precisar de exemplos
- `breaking-change` - Se a API mudou

**Uso:** Documentação de endpoints, APIs, integrações.

---

## Labels de Estado/Workflow

Estas labels são usadas para indicar o estado da issue no workflow:

### Estados de Desenvolvimento
- `ready` - Pronto para desenvolvimento
- `planning` - Planejada para futuros ciclos
- `analysis` - Em fase de análise
- `in-review` - Aguardando revisão
- `needs-information` - Requer mais informações
- `need-testing` - Precisa ser testado

### Estados de QA
- `qa-needed` - Requer validação do QA
- `qa-failed` - QA encontrou problemas
- `needs-tests` - PR exige testes adicionais

### Estados de Release
- `release-candidate` - Elegível para próxima release
- `release-blocker` - Impede finalização da release
- `ready-for-release` - Aprovado para release
- `changelog` - Deve aparecer no changelog

### Estados de Aprovação
- `needs-approval` - Aguardando aprovação
- `stakeholder-feedback` - Feedback de stakeholders
- `scope-change` - Mudança no escopo

### Estados Gerais
- `good-first-issue` - Bom para iniciantes
- `help-wanted` - Precisa de atenção extra
- `question` - Mais informações solicitadas
- `duplicate` - Issue duplicada
- `invalid` - Issue inválida
- `wontfix` - Não será trabalhada
- `resolved` - Resolvida

---

## Labels Específicas por Contexto

### Performance
- `slow-query` - Consultas lentas
- `memory-issue` - Problemas de memória
- `optimization` - Otimização necessária

### Segurança
- `security-audit` - Auditoria de segurança
- `vulnerability` - Vulnerabilidade
- `permissions` - Questões de acesso/ACL

### Infraestrutura
- `infra` - Infraestrutura
- `monitoring` - Monitoramento
- `environment` - Configuração de ambiente
- `deployment-issue` - Problemas de deploy
- `build-issue` - Problemas de build
- `ci-update` - Mudanças no CI

### Design/UX
- `design` - Relacionado a design
- `ui-bug` - Bug visual
- `visual-polish` - Ajuste visual fino
- `ux-improvement` - Melhoria de UX
- `ui-update` - Atualização de UI
- `ux-research` - Pesquisa de UX

### Documentação
- `documentation` - Documentação geral
- `api-docs` - Documentação de API
- `needs-examples` - Precisa de exemplos
- `internal-docs` - Documentação interna

### Qualidade de Código
- `technical-debt` - Dívida técnica
- `cleanup` - Limpeza de código
- `refactor` - Refatoração
- `deprecated` - Obsoleto
- `chore` - Tarefa simples

### Impacto
- `critical` - Crítico
- `breaking-change` - Quebra compatibilidade
- `small-change` - Mudança pequena

---

## Como Escolher o Template Correto

1. **É um bug?** → Use `bug-report.md` ou `design-bug.md`
2. **É uma nova feature?** → Use `feature-request.md`
3. **É uma tarefa geral?** → Use `task.md`
4. **É sobre dependências?** → Use `dependency.md`
5. **É sobre componente?** → Use `component.md`
6. **É um problema de design/UI?** → Use `design-bug.md`
7. **É um erro na documentação?** → Use `doc-bug-report.md`
8. **É uma solicitação de documentação?** → Use `documentation-request.md` ou `api-docs.md`
9. **É uma mudança arquitetural?** → Use `architecture.md`
10. **É uma questão de segurança?** → Use `security-audit.md` ou `vulnerability.md`
11. **É um incidente?** → Use `incident.md`
12. **É um problema de cliente?** → Use `customer-issue.md`
13. **É dívida técnica?** → Use `technical-debt.md`
14. **É uma otimização?** → Use `optimization.md`

---

## Boas Práticas

1. **Sempre use o template apropriado** - Não use templates genéricos quando há um específico
2. **Aplique labels relevantes** - Ajuda na organização e busca
3. **Complete todos os campos** - Quanto mais informações, melhor
4. **Use múltiplas labels quando apropriado** - Ex: `bug` + `critical` + `ui-bug`
5. **Atualize labels conforme a issue evolui** - Ex: `in-review` → `qa-needed` → `ready-for-release`
6. **Marque issues duplicadas** - Use `duplicate` e referencie a issue original
7. **Use `help-wanted` para issues que precisam de contribuidores**
8. **Use `good-first-issue` para issues adequadas para iniciantes**

---

## Exemplos de Uso

### Exemplo 1: Bug de Performance
- **Template:** `bug-report.md`
- **Labels:** `bug`, `slow-query`, `optimization`, `critical`

### Exemplo 2: Feature com Breaking Change
- **Template:** `feature-request.md`
- **Labels:** `enhancement`, `breaking-change`, `needs-approval`, `scope-change`

### Exemplo 3: Incidente de Produção
- **Template:** `incident.md`
- **Labels:** `incident`, `critical`, `release-blocker`

### Exemplo 4: Refatoração de Componente
- **Template:** `component.md`
- **Labels:** `component`, `refactor`, `technical-debt`

### Exemplo 5: Vulnerabilidade de Segurança
- **Template:** `vulnerability.md`
- **Labels:** `vulnerability`, `security`, `critical`, `do-not-merge`

