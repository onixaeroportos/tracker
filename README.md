# 📋 Onix Tracker

Coleção abrangente de templates para Issues e Pull Requests do GitHub, organizados para facilitar o gerenciamento de projetos e melhorar a comunicação da equipe.

## 📖 Sobre

O **Onix Tracker** fornece um conjunto completo de templates padronizados para Issues e Pull Requests, cobrindo diversos tipos de trabalho em projetos de software. Estes templates ajudam a:

- ✅ Padronizar o processo de criação de issues e PRs
- ✅ Capturar informações relevantes de forma consistente
- ✅ Facilitar a triagem e revisão
- ✅ Melhorar a comunicação entre membros da equipe
- ✅ Documentar decisões e mudanças adequadamente

## 🚀 Funcionalidades

### 📝 Templates de Issues (16 tipos)

1. **Bug Report** - Relatório de bugs e problemas
2. **Feature Request** - Solicitação de novas funcionalidades
3. **Task** - Tarefas de trabalho gerais
4. **Dependency** - Gerenciamento de dependências
5. **Component** - Criação/modificação de componentes
6. **Design Bug** - Problemas de design e UI
7. **Doc Bug Report** - Erros na documentação
8. **Documentation Request** - Solicitação de documentação
9. **Architecture** - Mudanças arquiteturais
10. **Security Audit** - Auditorias de segurança
11. **Vulnerability** - Vulnerabilidades de segurança
12. **Incident** - Incidentes de produção
13. **Customer Issue** - Problemas reportados por clientes
14. **Technical Debt** - Dívida técnica
15. **Optimization** - Otimizações de performance
16. **API Documentation** - Documentação específica de APIs

### 🔄 Templates de Pull Requests (9 tipos)

1. **Template Padrão** - Template abrangente para qualquer tipo de PR
2. **Bug Fix** - Correções de bugs
3. **Feature** - Novas funcionalidades
4. **Security** - Correções e melhorias de segurança
5. **Documentation** - Mudanças na documentação
6. **Refactor** - Refatorações de código
7. **Performance** - Otimizações de performance
8. **Dependency** - Atualizações de dependências
9. **Infrastructure** - Mudanças em infraestrutura e CI/CD

## 📁 Estrutura do Projeto

```
tracker/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── api-docs.md
│   │   ├── architecture.md
│   │   ├── bug-report.md
│   │   ├── component.md
│   │   ├── customer-issue.md
│   │   ├── dependency.md
│   │   ├── design-bug.md
│   │   ├── doc-bug-report.md
│   │   ├── documentation-request.md
│   │   ├── feature-request.md
│   │   ├── incident.md
│   │   ├── optimization.md
│   │   ├── security-audit.md
│   │   ├── task.md
│   │   ├── technical-debt.md
│   │   ├── vulnerability.md
│   │   └── README.md
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── PULL_REQUEST_TEMPLATE/
│       ├── bug-fix.md
│       ├── dependency.md
│       ├── documentation.md
│       ├── feature.md
│       ├── infrastructure.md
│       ├── performance.md
│       ├── refactor.md
│       ├── security.md
│       └── README.md
├── LICENSE
└── README.md
```

## 🛠️ Instalação

### Método 1: Copiar Arquivos Manualmente

1. Clone ou baixe este repositório
2. Copie o diretório `.github` para a raiz do seu repositório
3. Faça commit das mudanças

```bash
git clone https://github.com/seu-usuario/onix.git
cp -r onix/tracker/.github /caminho/para/seu/repositorio/
cd /caminho/para/seu/repositorio
git add .github
git commit -m "docs: adiciona templates de issues e PRs"
git push
```

### Método 2: Usar como Template

1. Use este repositório como template ao criar um novo repositório
2. Ou copie apenas os templates que você precisa

## 📚 Como Usar

### Templates de Issues

1. Vá para a página de Issues do seu repositório no GitHub
2. Clique em "New Issue"
3. Selecione o template apropriado para o tipo de issue
4. Preencha todas as seções relevantes
5. Remova ou marque como N/A seções não aplicáveis
6. Adicione labels apropriadas
7. Submeta a issue

### Templates de Pull Requests

1. Crie um novo Pull Request no GitHub
2. Selecione "Choose template" (se múltiplos templates estiverem disponíveis)
3. Escolha o template apropriado para o tipo de mudança
4. Preencha todas as seções relevantes
5. Mencione issues relacionadas usando `Resolve #123`
6. Adicione screenshots/vídeos se aplicável
7. Marque checkboxes relevantes
8. Solicite revisores
9. Submeta o PR

## 🎯 Guia de Seleção de Templates

### Para Issues

| Situação | Template Recomendado |
|----------|---------------------|
| Algo não está funcionando | `bug-report.md` |
| Nova funcionalidade desejada | `feature-request.md` |
| Tarefa de trabalho geral | `task.md` |
| Gerenciar dependências | `dependency.md` |
| Criar/modificar componente | `component.md` |
| Problema visual/UI | `design-bug.md` |
| Erro na documentação | `doc-bug-report.md` |
| Solicitar documentação | `documentation-request.md` ou `api-docs.md` |
| Mudança arquitetural | `architecture.md` |
| Auditoria de segurança | `security-audit.md` |
| Vulnerabilidade encontrada | `vulnerability.md` |
| Incidente em produção | `incident.md` |
| Problema de cliente | `customer-issue.md` |
| Dívida técnica | `technical-debt.md` |
| Otimização necessária | `optimization.md` |

### Para Pull Requests

| Tipo de Mudança | Template Recomendado |
|----------------|---------------------|
| Correção de bug | `bug-fix.md` |
| Nova funcionalidade | `feature.md` |
| Correção de segurança | `security.md` |
| Mudança na documentação | `documentation.md` |
| Refatoração | `refactor.md` |
| Otimização | `performance.md` |
| Atualizar dependências | `dependency.md` |
| Mudança em infraestrutura | `infrastructure.md` |
| Qualquer tipo | `PULL_REQUEST_TEMPLATE.md` (padrão) |

## 🏷️ Labels e Organização

### Labels Principais por Tipo

#### Issues
- `bug` - Bugs e problemas
- `enhancement` - Novas features
- `task` - Tarefas gerais
- `documentation` - Documentação
- `security` - Segurança
- `performance` - Performance
- `refactor` - Refatoração
- `technical-debt` - Dívida técnica

#### Estados/Workflow
- `ready` - Pronto para desenvolvimento
- `in-review` - Em revisão
- `qa-needed` - Precisa de QA
- `needs-approval` - Precisa aprovação
- `blocked` - Bloqueado
- `wontfix` - Não será corrigido

#### Prioridade
- `critical` - Crítico
- `high-priority` - Alta prioridade
- `medium-priority` - Média prioridade
- `low-priority` - Baixa prioridade

Para uma lista completa de labels e quando usá-las, consulte os arquivos README.md dentro dos diretórios de templates.

## 💡 Boas Práticas

### Para Issues

1. ✅ Use sempre o template apropriado
2. ✅ Preencha todas as seções relevantes
3. ✅ Forneça informações suficientes para reprodução/entendimento
4. ✅ Adicione screenshots/logs quando apropriado
5. ✅ Use labels corretamente para facilitar triagem
6. ✅ Mencione issues relacionadas
7. ✅ Atualize o status conforme a issue evolui

### Para Pull Requests

1. ✅ Use o template apropriado
2. ✅ Relacione com issues usando `Resolve #123`
3. ✅ Descreva claramente o que foi feito e por quê
4. ✅ Forneça instruções de como testar
5. ✅ Adicione screenshots para mudanças visuais
6. ✅ Marque breaking changes claramente
7. ✅ Complete checklists relevantes
8. ✅ Mantenha PRs focados (uma mudança por PR)
9. ✅ Solicite revisores apropriados

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Fork o repositório
2. Crie uma branch para sua feature (`git checkout -b feature/minha-feature`)
3. Faça suas mudanças
4. Commit suas mudanças (`git commit -m 'feat: adiciona novo template'`)
5. Push para a branch (`git push origin feature/minha-feature`)
6. Abra um Pull Request

### Diretrizes de Contribuição

- Mantenha consistência com os templates existentes
- Adicione documentação adequada
- Teste os templates antes de submeter
- Siga as convenções de nomenclatura estabelecidas
- Adicione exemplos quando apropriado

## 📄 Licença

Este projeto está licenciado sob a **GNU Affero General Public License v3.0** (AGPL-3.0).

Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📖 Documentação Adicional

- [Guia de Templates de Issues](.github/ISSUE_TEMPLATE/README.md)
- [Guia de Templates de Pull Requests](.github/PULL_REQUEST_TEMPLATE/README.md)

## 🔗 Links Úteis

- [GitHub Issues](https://github.com/features/issues)
- [GitHub Pull Requests](https://github.com/features/pull-requests)
- [GitHub Issue Templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates)
- [GNU AGPL v3](https://www.gnu.org/licenses/agpl-3.0.html)

## 📊 Estatísticas

- **16** Templates de Issues
- **9** Templates de Pull Requests
- **50+** Labels recomendadas
- **100%** Documentação em Português

## 🙏 Agradecimentos

Agradecemos a todos que contribuem para melhorar estes templates e torná-los mais úteis para a comunidade.

## 📞 Suporte

Se você encontrar problemas ou tiver sugestões:

1. Abra uma [Issue](https://github.com/seu-usuario/onix/issues)
2. Use o template apropriado para sua situação
3. Forneça informações detalhadas

---

**Feito com ❤️ para melhorar o gerenciamento de projetos**

