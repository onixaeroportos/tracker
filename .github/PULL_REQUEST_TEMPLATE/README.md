# Pull Request Templates - Guia de Referência

Este diretório contém templates para diferentes tipos de Pull Requests. Use este guia para escolher o template correto.

## Templates Disponíveis

### Template Padrão
**Arquivo:** `../PULL_REQUEST_TEMPLATE.md` (na raiz do diretório `.github`)

**Quando usar:** Template abrangente para qualquer tipo de PR. Use quando nenhum template específico se adequar.

---

### 1. Bug Fix (`bug-fix.md`)
**Quando usar:** Para PRs que corrigem bugs.

**Labels padrão:** `bug`, `bug-fix`

**Labels adicionais recomendadas:**
- `ui-bug` - Se for bug visual
- `critical` - Se for crítico
- `config-error`, `build-issue`, `deployment-issue` - Se aplicável

**Uso:** Correções de bugs técnicos ou funcionais.

---

### 2. Feature (`feature.md`)
**Quando usar:** Para PRs que adicionam novas funcionalidades.

**Labels padrão:** `enhancement`, `feature`

**Labels adicionais recomendadas:**
- `breaking-change` - Se quebrar compatibilidade
- `ux-improvement` - Melhorias de UX
- `needs-approval` - Se precisar aprovação
- `scope-change` - Se mudou escopo

**Uso:** Novas features, melhorias, adições de funcionalidade.

---

### 3. Security (`security.md`)
**Quando usar:** Para PRs relacionados a segurança.

**Labels padrão:** `security`, `vulnerability`

**Labels adicionais recomendadas:**
- `critical` - Sempre aplicar
- `do-not-merge` - Até aprovação de segurança
- `security-audit` - Se relacionado a auditoria

**Uso:** Correções de vulnerabilidades, melhorias de segurança, auditorias.

---

### 4. Documentation (`documentation.md`)
**Quando usar:** Para PRs de documentação.

**Labels padrão:** `documentation`

**Labels adicionais recomendadas:**
- `api-docs` - Se for documentação de API
- `internal-docs` - Se for documentação interna
- `needs-examples` - Se precisa de exemplos

**Uso:** Criação, atualização ou correção de documentação.

---

### 5. Refactor (`refactor.md`)
**Quando usar:** Para PRs de refatoração.

**Labels padrão:** `refactor`, `technical-debt`

**Labels adicionais recomendadas:**
- `cleanup` - Limpeza de código
- `deprecated` - Remoção de código obsoleto
- `component` - Se for refatoração de componente

**Uso:** Refatorações de código, limpeza, redução de dívida técnica.

---

### 6. Performance (`performance.md`)
**Quando usar:** Para PRs de otimização de performance.

**Labels padrão:** `optimization`, `performance`

**Labels adicionais recomendadas:**
- `slow-query` - Otimização de banco
- `memory-issue` - Otimização de memória

**Uso:** Otimizações de performance, consultas lentas, uso de memória.

---

### 7. Dependency (`dependency.md`)
**Quando usar:** Para PRs que atualizam dependências.

**Labels padrão:** `dependency`, `dependencies`

**Labels adicionais recomendadas:**
- `version-update` - Atualização de versão
- `breaking-change` - Se a atualização quebrar compatibilidade

**Uso:** Adicionar, atualizar ou remover dependências.

---

### 8. Infrastructure (`infrastructure.md`)
**Quando usar:** Para PRs de infraestrutura, CI/CD, deploy.

**Labels padrão:** `infra`, `infrastructure`

**Labels adicionais recomendadas:**
- `ci-update` - Mudanças no CI
- `deployment-issue` - Problemas de deploy
- `environment` - Configuração de ambiente
- `monitoring` - Monitoramento

**Uso:** Mudanças em infraestrutura, CI/CD, configurações de ambiente.

---

## Como Usar os Templates

### No GitHub

1. Ao criar um PR, você verá a opção "Choose template" no editor
2. Selecione o template apropriado
3. Preencha todas as seções relevantes
4. Remova seções não aplicáveis ou marque como N/A

### Localmente

1. Use `PULL_REQUEST_TEMPLATE.md` como base
2. Copie o template específico se preferir
3. Preencha antes de criar o PR

---

## Mapeamento: Issue → PR Template

| Tipo de Issue | Template de PR Recomendado |
|--------------|---------------------------|
| Bug Report | `bug-fix.md` |
| Feature Request | `feature.md` |
| Task | Template padrão ou `refactor.md` |
| Dependency | `dependency.md` |
| Component | `feature.md` ou template padrão |
| Design Bug | `bug-fix.md` |
| Doc Bug Report | `documentation.md` |
| Documentation Request | `documentation.md` |
| Architecture | Template padrão |
| Security Audit | `security.md` |
| Vulnerability | `security.md` |
| Incident | `bug-fix.md` |
| Customer Issue | `bug-fix.md` |
| Technical Debt | `refactor.md` |
| Optimization | `performance.md` |
| API Documentation | `documentation.md` |

---

## Checklist Geral de PR

Sempre verifique antes de criar um PR:

### Código
- [ ] Código segue padrões do projeto
- [ ] Auto-revisão realizada
- [ ] Sem warnings ou erros
- [ ] Comentários adicionados onde necessário

### Testes
- [ ] Testes adicionados/atualizados
- [ ] Todos os testes passam
- [ ] Cobertura de testes mantida

### Documentação
- [ ] Documentação atualizada
- [ ] Changelog atualizado
- [ ] Exemplos fornecidos (se necessário)

### Segurança
- [ ] Sem vulnerabilidades introduzidas
- [ ] Dados sensíveis protegidos
- [ ] Validações implementadas

### Build/CI
- [ ] Build passa
- [ ] CI passa
- [ ] Sem erros de linting

---

## Boas Práticas

1. **Use o template apropriado** - Facilita revisão e entendimento
2. **Complete todas as seções relevantes** - Quanto mais informações, melhor
3. **Mencione issues relacionadas** - Use `Resolve #123` para fechar issues
4. **Adicione screenshots** - Especialmente para mudanças visuais
5. **Descreva como testar** - Facilita validação pelos revisores
6. **Marque breaking changes** - Importante para comunicação
7. **Solicite revisores apropriados** - Use @mentions quando necessário
8. **Atualize checklist** - Mostra o que foi verificado
9. **Mantenha PRs focados** - Um PR por feature/bug
10. **Peque mudanças** - PRs pequenos são mais fáceis de revisar

---

## Labels de PR

Use labels apropriadas para facilitar organização:

### Por Tipo
- `bug`, `bug-fix`
- `enhancement`, `feature`
- `documentation`
- `refactor`
- `security`
- `performance`, `optimization`
- `dependency`, `dependencies`
- `infrastructure`, `infra`

### Por Prioridade
- `critical`
- `high-priority`
- `medium-priority`
- `low-priority`

### Por Status
- `needs-review`
- `ready-for-review`
- `needs-tests`
- `needs-qa`
- `do-not-merge`
- `ready-for-release`
- `release-blocker`

### Por Impacto
- `breaking-change`
- `small-change`

### Por Área
- `ui`, `frontend`
- `backend`
- `api`
- `database`
- `infrastructure`

---

## Exemplos de Uso

### Exemplo 1: Bug Fix Simples
**Template:** `bug-fix.md`
**Labels:** `bug`, `bug-fix`

### Exemplo 2: Nova Feature com Breaking Change
**Template:** `feature.md`
**Labels:** `enhancement`, `feature`, `breaking-change`, `needs-approval`

### Exemplo 3: Correção de Vulnerabilidade
**Template:** `security.md`
**Labels:** `security`, `vulnerability`, `critical`, `do-not-merge`

### Exemplo 4: Refatoração de Código
**Template:** `refactor.md`
**Labels:** `refactor`, `technical-debt`

### Exemplo 5: Otimização de Performance
**Template:** `performance.md`
**Labels:** `optimization`, `performance`, `slow-query`

---

## Notas Importantes

- **Breaking Changes**: Sempre documente detalhadamente
- **Segurança**: PRs de segurança requerem aprovação específica
- **Performance**: Inclua métricas de antes/depois
- **Dependências**: Verifique vulnerabilidades conhecidas
- **Infraestrutura**: Teste em staging antes de produção
- **Documentação**: Mantenha sempre atualizada

---

**Para mais informações sobre issues, consulte:** `../ISSUE_TEMPLATE/README.md`

