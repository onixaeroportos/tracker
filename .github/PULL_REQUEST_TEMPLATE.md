---
name: Pull Request
about: Template padrão para Pull Requests
title: ''
labels: ''
assignees: onixaeroporto, reeseae64
---

## Tipo de Mudança

Marque o tipo de mudança deste PR:

- [ ] 🐛 Bug fix (correção de bug)
- [ ] ✨ Feature (nova funcionalidade)
- [ ] 🔧 Task (tarefa de trabalho)
- [ ] 📦 Dependency (gerenciamento de dependências)
- [ ] 🧩 Component (componente)
- [ ] 🎨 Design Bug (problema de design/UI)
- [ ] 📝 Documentation (documentação)
- [ ] 🏗️ Architecture (mudança arquitetural)
- [ ] 🔒 Security (segurança)
- [ ] 🚨 Incident Fix (correção de incidente)
- [ ] 👤 Customer Issue (problema de cliente)
- [ ] 🧹 Technical Debt (dívida técnica)
- [ ] ⚡ Optimization (otimização)
- [ ] 📚 API Documentation (documentação de API)
- [ ] 🔄 Refactor (refatoração)
- [ ] 🧪 Test (testes)
- [ ] 🏃 Performance (performance)
- [ ] 🔧 Configuration (configuração)
- [ ] 🐳 Infrastructure (infraestrutura)
- [ ] 🔨 Build/CI (build ou CI)

## Descrição

Descreva de forma clara e concisa o que este PR faz e por quê.

## Issues Relacionadas

Relaciona este PR às issues que resolve:

- Resolve #
- Relacionado a #
- Fecha #
- Fecha parcialmente #

## Mudanças Realizadas

Liste as principais mudanças implementadas:

- Mudança 1
- Mudança 2
- Mudança 3

## Como Testar

Descreva os passos para testar as mudanças:

1. Passo 1: Faça '...'
2. Passo 2: Navegue até '...'
3. Passo 3: Verifique que '...'
4. Passo 4: Confirme que '...'

## Screenshots/Vídeos

Se aplicável, adicione screenshots ou vídeos demonstrando as mudanças:

### Antes
[Screenshot ou descrição do estado anterior]

### Depois
[Screenshot ou descrição do novo estado]

## Breaking Changes

- [ ] Esta PR introduz breaking changes
- [ ] Esta PR NÃO introduz breaking changes

Se há breaking changes, descreva-os e explique como migrar:

### O que mudou?

### Como migrar?

## Checklist de Revisão

### Código
- [ ] Meu código segue os padrões do projeto
- [ ] Realizei auto-revisão do código
- [ ] Comentei partes complexas do código
- [ ] Minhas mudanças não geram warnings
- [ ] Atualizei a documentação conforme necessário

### Testes
- [ ] Adicionei testes que provam que minha correção é efetiva
- [ ] Novos e antigos testes passam localmente
- [ ] Testes unitários passam
- [ ] Testes de integração passam
- [ ] Testes E2E passam (se aplicável)
- [ ] Testes de performance realizados (se aplicável)

### Documentação
- [ ] Atualizei a documentação técnica
- [ ] Atualizei a documentação de usuário (se aplicável)
- [ ] Atualizei o changelog
- [ ] Adicionei exemplos de uso (se aplicável)
- [ ] Atualizei comentários no código

### Segurança
- [ ] Não introduzo vulnerabilidades de segurança
- [ ] Dados sensíveis estão protegidos
- [ ] Validações de entrada estão implementadas
- [ ] Permissões e ACL verificadas (se aplicável)
- [ ] Auditoria de segurança realizada (se necessário)

### Performance
- [ ] Não introduzo problemas de performance
- [ ] Otimizações aplicadas quando necessário
- [ ] Consultas ao banco de dados otimizadas (se aplicável)
- [ ] Uso de memória verificado
- [ ] Métricas de performance coletadas (se aplicável)

### Dependências
- [ ] Dependências adicionadas são necessárias
- [ ] Versões de dependências estão atualizadas
- [ ] Não há conflitos de dependências
- [ ] Vulnerabilidades conhecidas verificadas

### Build e Deploy
- [ ] Build passa localmente
- [ ] Build passa no CI
- [ ] Sem erros de linting
- [ ] Testes de integração contínua passam
- [ ] Deploy testado em ambiente de staging (se aplicável)

### UI/UX (se aplicável)
- [ ] Mudanças visuais consistentes com o design system
- [ ] Responsividade verificada
- [ ] Acessibilidade verificada
- [ ] Testado em diferentes navegadores
- [ ] Testado em diferentes dispositivos/resoluções

### Checklist Específico por Tipo

#### 🐛 Bug Fix
- [ ] Passos para reproduzir verificados
- [ ] Comportamento esperado validado
- [ ] Regressões testadas
- [ ] Root cause identificado

#### ✨ Feature
- [ ] Funcionalidade implementada conforme especificação
- [ ] Casos de uso cobertos
- [ ] Edge cases tratados
- [ ] Feedback de stakeholders incorporado (se aplicável)

#### 🏗️ Architecture
- [ ] Mudanças arquiteturais documentadas
- [ ] Diagramas atualizados (se aplicável)
- [ ] Migração testada
- [ ] Rollback planejado

#### 🔒 Security
- [ ] Vulnerabilidade corrigida
- [ ] Testes de segurança realizados
- [ ] Aprovação de segurança obtida (se necessário)

#### ⚡ Optimization
- [ ] Métricas de melhoria documentadas
- [ ] Benchmark realizado
- [ ] Melhoria de performance validada

#### 📚 API Documentation
- [ ] Endpoints documentados
- [ ] Exemplos de uso fornecidos
- [ ] Códigos de status HTTP documentados
- [ ] Tratamento de erros documentado

## Ambiente de Teste

Descreva o ambiente onde as mudanças foram testadas:

- SO: [ex: Ubuntu 22.04, Windows 11, macOS 13]
- Navegador: [ex: Chrome 120, Firefox 121, Safari]
- Versão Node: [ex: 18.x, 20.x]
- Versão da aplicação: [ex: 1.0.0]
- Ambiente: [ex: desenvolvimento, staging, produção]

## Dependências

Liste PRs ou issues que devem ser mergeadas antes deste:

- Precisa de #
- Dependente de #

## Relacionado a

Liste PRs, issues ou discussões relacionadas:

- Relacionado a #
- Continuação de #
- Alternativa para #

## Impacto

### Impacto no Sistema
- [ ] Sem impacto em outras funcionalidades
- [ ] Impacto em funcionalidades existentes (descrever abaixo)
- [ ] Requer mudanças em outras partes do código
- [ ] Requer migração de dados

### Impacto nos Usuários
- [ ] Transparente para usuários
- [ ] Requer ação dos usuários
- [ ] Requer treinamento/documentação adicional

### Impacto na Infraestrutura
- [ ] Sem mudanças na infraestrutura
- [ ] Requer mudanças na infraestrutura (descrever abaixo)
- [ ] Requer novas dependências de infraestrutura

Descreva o impacto em detalhes se necessário:

## Métricas e Monitoramento

Se aplicável, descreva métricas que devem ser monitoradas:

- Métrica 1: [descrição e valores esperados]
- Métrica 2: [descrição e valores esperados]

## Notas Adicionais

Adicione qualquer outra informação relevante:

- Contexto adicional
- Decisões de design
- Alternativas consideradas
- Lições aprendidas
- Próximos passos

## Aprovações Necessárias

- [ ] Aprovação técnica necessária: @mention
- [ ] Aprovação de produto necessária: @mention
- [ ] Aprovação de segurança necessária: @mention
- [ ] Aprovação de design necessária: @mention
- [ ] Aprovação de QA necessária: @mention

## Labels Sugeridas

Sugira labels apropriadas para este PR (o revisor pode ajustar):

- [ ] `bug` / `enhancement` / `task` / `documentation` / etc.
- [ ] `critical` / `high-priority` / `medium-priority` / `low-priority`
- [ ] `breaking-change` / `small-change`
- [ ] `needs-review` / `ready-for-review`
- [ ] `needs-tests` / `needs-qa`
- [ ] `security` / `performance` / `optimization`
- [ ] `ui` / `backend` / `frontend` / `infrastructure`
- [ ] `do-not-merge` (remover após aprovações)

---

**Por favor, preencha todas as seções relevantes antes de solicitar revisão. Seções não aplicáveis podem ser deixadas em branco ou marcadas como N/A.**

