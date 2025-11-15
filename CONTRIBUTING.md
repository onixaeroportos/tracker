# 🤝 Guia de Contribuição

Obrigado por considerar contribuir para o **Onix Tracker**! Este documento fornece diretrizes e informações sobre como contribuir para este projeto.

## 📋 Índice

- [Código de Conduta](#-código-de-conduta)
- [Como Contribuir](#-como-contribuir)
  - [Reportando Bugs](#reportando-bugs)
  - [Sugerindo Melhorias](#sugerindo-melhorias)
  - [Adicionando Templates](#adicionando-templates)
  - [Melhorando Documentação](#melhorando-documentação)
- [Processo de Desenvolvimento](#-processo-de-desenvolvimento)
- [Padrões de Código](#-padrões-de-código)
- [Convenções de Commits](#-convenções-de-commits)
- [Criando Pull Requests](#-criando-pull-requests)
- [Revisão de Código](#-revisão-de-código)
- [Perguntas Frequentes](#-perguntas-frequentes)

## 📜 Código de Conduta

Ao participar deste projeto, você concorda em manter nosso Código de Conduta:

- **Seja respeitoso** - Trate todos com respeito e consideração
- **Seja inclusivo** - Aceite diferentes pontos de vista e experiências
- **Seja construtivo** - Forneça feedback útil e construtivo
- **Seja profissional** - Mantenha um ambiente profissional e acolhedor

Comportamento inadequado não será tolerado e pode resultar em remoção do projeto.

## 🚀 Como Contribuir

### Reportando Bugs

Se você encontrou um bug, por favor:

1. **Verifique se já existe uma issue** sobre o problema
2. **Use o template `bug-report.md`** ao criar uma nova issue
3. **Forneça informações detalhadas**:
   - Descrição clara do bug
   - Passos para reproduzir
   - Comportamento esperado vs. atual
   - Ambiente (OS, navegador, versões)
   - Screenshots/logs quando aplicável

#### Exemplo de Issue de Bug

```
Título: [BUG] Template X não está renderizando corretamente

Descrição:
O template Y não está sendo exibido corretamente quando...

Passos para Reproduzir:
1. Vá para...
2. Clique em...
3. Veja o erro em...

Comportamento Esperado:
O template deveria...

Comportamento Atual:
O template está...
```

### Sugerindo Melhorias

Para sugerir melhorias ou novas funcionalidades:

1. **Use o template `feature-request.md`**
2. **Descreva claramente** o problema que resolve ou a necessidade
3. **Explique como a solução proposta funcionaria**
4. **Considere alternativas** e explique por que a sua é melhor
5. **Inclua exemplos** ou mockups se aplicável

#### Exemplo de Feature Request

```
Título: [FEATURE] Adicionar template para DevOps

Descrição:
Seria útil ter um template específico para issues de DevOps que inclua...

Problema que Resolve:
Atualmente, issues de DevOps usam template genérico que não captura...

Solução Proposta:
Um novo template que inclua campos para...
```

### Adicionando Templates

Para adicionar novos templates:

1. **Verifique a necessidade** - Discuta na comunidade antes de criar
2. **Siga a estrutura existente** - Use templates atuais como referência
3. **Mantenha consistência** - Use o mesmo formato e estilo
4. **Documente adequadamente** - Adicione ao README apropriado
5. **Teste localmente** - Verifique se o template funciona corretamente

#### Estrutura de um Template de Issue

```markdown
---
name: Nome do Template
about: Descrição breve do que o template é para
title: '[PREFIXO] '
labels: label1, label2
---

## Seção 1
Descrição da seção 1

## Seção 2
Descrição da seção 2

## Checklist
- [ ] Item 1
- [ ] Item 2

## Informações Adicionais
Adicione informações adicionais aqui.
```

#### Estrutura de um Template de PR

```markdown
---
name: Nome do Template
about: Descrição breve do template
title: '[PREFIXO] '
labels: label1, label2
---

## Descrição
Descrição do que o PR faz

## Issue Relacionada
- Resolve #

## Checklist
- [ ] Item 1
- [ ] Item 2
```

### Melhorando Documentação

Melhorias na documentação são sempre bem-vindas:

- Corrija erros ortográficos ou gramaticais
- Melhore clareza e legibilidade
- Adicione exemplos ou casos de uso
- Atualize informações desatualizadas
- Adicione traduções (quando relevante)
- Melhore a estrutura e organização

Use o template `doc-bug-report.md` ou `documentation-request.md` conforme apropriado.

## 🔄 Processo de Desenvolvimento

### 1. Fork e Clone

```bash
git clone https://github.com/onixaeroportos/[repositorio].git
cd onix/[repositorio]
```

### 2. Criar Branch

Crie uma branch descritiva para sua mudança:

```bash
git checkout -b feature/nome-da-feature
# ou
git checkout -b fix/correcao-do-bug
# ou
git checkout -b docs/melhorias-na-documentacao
```

#### Convenções de Nomenclatura de Branches

- `feature/` - Para novas funcionalidades
- `fix/` - Para correções de bugs
- `docs/` - Para mudanças na documentação
- `refactor/` - Para refatorações
- `test/` - Para adição de testes
- `chore/` - Para tarefas de manutenção

### 3. Fazer Mudanças

- Faça suas mudanças no código/documentação
- Siga os padrões estabelecidos
- Teste suas mudanças localmente
- Mantenha commits pequenos e focados

### 4. Commit

Use mensagens de commit descritivas seguindo o padrão:

```bash
git add .
git commit -m "tipo(escopo): descrição curta

Descrição mais detalhada se necessário

Resolve #123"
```

### 5. Push e Pull Request

```bash
git push origin feature/nome-da-feature
```

Depois, abra um Pull Request no GitHub usando o template apropriado.

## 📐 Padrões de Código

### Estrutura de Templates

1. **Front Matter (YAML)** - Metadados do template
2. **Título/Descrição** - Contexto e propósito
3. **Seções Principais** - Campos de informação
4. **Checklists** - Quando apropriado
5. **Informações Adicionais** - Campo livre

### Formatação Markdown

- Use cabeçalhos hierárquicos (`##`, `###`)
- Mantenha listas consistentes
- Use checkboxes quando apropriado (`- [ ]`)
- Mantenha linhas em até 100 caracteres
- Use emojis de forma consistente e moderada

### Consistência

- Siga o estilo dos templates existentes
- Mantenha linguagem clara e objetiva
- Use termos consistentes em todo o projeto
- Mantenha estrutura similar entre templates similares

### Exemplo de Template Bem Formatado

```markdown
---
name: Example Template
about: Template de exemplo
title: '[EXAMPLE] '
labels: example
---

## Descrição
Descrição clara e concisa do que este template é para.

## Detalhes
Liste informações importantes:
- Item 1
- Item 2

## Checklist
- [ ] Verificação 1
- [ ] Verificação 2

## Informações Adicionais
Adicione qualquer informação adicional relevante.
```

## 💬 Convenções de Commits

Seguimos o padrão [Conventional Commits](https://www.conventionalcommits.org/):

### Formato

```
<tipo>(<escopo>): <descrição curta>

<descrição detalhada opcional>

<rodapé opcional>
```

### Tipos

- `feat` - Nova funcionalidade
- `fix` - Correção de bug
- `docs` - Mudanças na documentação
- `style` - Formatação, pontuação, etc (sem mudança de código)
- `refactor` - Refatoração de código
- `test` - Adição ou correção de testes
- `chore` - Tarefas de manutenção
- `perf` - Melhorias de performance
- `ci` - Mudanças em CI/CD
- `build` - Mudanças no sistema de build

### Exemplos

```bash
feat(templates): adiciona template para DevOps issues

Adiciona novo template específico para questões de DevOps
incluindo campos para infraestrutura, CI/CD e deploy.

Resolve #42
```

```bash
fix(bug-report): corrige campo de ambiente no template

Corrige formatação do campo de ambiente que estava
quebrando a renderização do template.

Fixes #38
```

```bash
docs(readme): atualiza instruções de instalação

Adiciona novo método de instalação usando npm
e melhora clareza das instruções existentes.
```

## 🔀 Criando Pull Requests

### Antes de Criar um PR

- [ ] Código/documentação segue os padrões do projeto
- [ ] Mudanças foram testadas localmente
- [ ] Commits seguem as convenções estabelecidas
- [ ] Branch está atualizada com a branch principal
- [ ] Não há conflitos de merge
- [ ] Documentação foi atualizada se necessário

### Usando Templates de PR

**Sempre use o template apropriado** ao criar um PR:

1. Selecione o template correto baseado no tipo de mudança
2. Preencha todas as seções relevantes
3. Mencione issues relacionadas usando `Resolve #123`
4. Adicione screenshots quando aplicável
5. Complete checklists relevantes

### Descrição do PR

Uma boa descrição de PR deve incluir:

- **O que** foi mudado
- **Por que** foi mudado
- **Como** testar as mudanças
- **Evidências** (screenshots, logs, etc)
- **Breaking changes** (se houver)
- **Issues relacionadas**

### Exemplo de Descrição de PR

```markdown
## O que foi mudado
Adiciona novo template para issues de DevOps que inclui campos
específicos para infraestrutura, CI/CD e deploy.

## Por que
Issues de DevOps estavam usando template genérico que não
capturava informações importantes como ambiente, tipo de deploy, etc.

## Como testar
1. Vá para "New Issue"
2. Selecione o template "DevOps"
3. Verifique que todos os campos estão presentes
4. Preencha e submeta uma issue de teste

## Checklist
- [x] Template segue estrutura estabelecida
- [x] Documentação atualizada
- [x] Testado localmente
- [x] README atualizado

Resolve #42
```

### Tamanho do PR

- **Mantenha PRs pequenos** - Fáceis de revisar
- **Um PR = uma mudança** - Evite misturar múltiplas mudanças
- **Se necessário, quebre em múltiplos PRs** - Facilita revisão

### Labels

Use labels apropriadas:
- Tipo: `bug`, `enhancement`, `documentation`, etc.
- Status: `ready-for-review`, `work-in-progress`, etc.
- Prioridade: `critical`, `high-priority`, etc.

## 👀 Revisão de Código

### Para Revisores

- Seja construtivo e respeitoso
- Explique o "porquê" de sugestões
- Reconheça boas práticas
- Aprove quando estiver satisfeito
- Solicite mudanças específicas quando necessário

### Para Autores

- Responda a todos os comentários
- Faça mudanças solicitadas ou explique por que não
- Peça esclarecimentos se necessário
- Atualize o PR quando fizer mudanças
- Agradeça feedback construtivo

### Processo de Revisão

1. **Revisão inicial** - Verificação de estrutura e padrões
2. **Feedback** - Comentários e sugestões
3. **Correções** - Autor faz ajustes
4. **Re-revisão** - Verificação das correções
5. **Aprovação** - PR aprovado e pronto para merge
6. **Merge** - Integração na branch principal

## ❓ Perguntas Frequentes

### Como escolho o template correto?

Consulte os READMEs:
- [Guia de Templates de Issues](.github/ISSUE_TEMPLATE/README.md)
- [Guia de Templates de PRs](.github/PULL_REQUEST_TEMPLATE/README.md)

### Preciso de permissão para contribuir?

Não! Todos são bem-vindos a contribuir. Basta fazer fork e criar um PR.

### Como adiciono um novo tipo de template?

1. Abra uma issue discutindo a necessidade
2. Crie o template seguindo a estrutura existente
3. Adicione documentação apropriada
4. Abra um PR com a mudança

### E se não tenho certeza se minha contribuição é apropriada?

Não há problema! Abra uma issue discutindo sua ideia antes de começar a trabalhar.

### Como faço para traduzir templates?

1. Crie uma issue solicitando tradução
2. Ou faça fork, traduza e abra um PR
3. Mantenha a estrutura original
4. Atualize documentação se necessário

### Qual é o tempo de resposta para revisões?

Geralmente respondemos em 2-3 dias úteis. Para issues urgentes, marque como `critical`.

### Preciso assinar um CLA (Contributor License Agreement)?

Não, mas ao contribuir, você concorda que suas contribuições serão licenciadas sob a AGPL-3.0.

### Como reporto comportamento inadequado?

Entre em contato com os mantenedores do projeto através de mensagem privada ou email.

## 📚 Recursos Adicionais

- [README do Projeto](README.md)
- [Guia de Templates de Issues](.github/ISSUE_TEMPLATE/README.md)
- [Guia de Templates de PRs](.github/PULL_REQUEST_TEMPLATE/README.md)
- [Documentação do GitHub sobre Templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates)

## 🙏 Agradecimentos

Agradecemos por considerar contribuir para o Onix Tracker! Suas contribuições tornam este projeto melhor para toda a comunidade.

---

**Última atualização:** 2024

**Mantido com ❤️ pela comunidade**
