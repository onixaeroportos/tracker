---
name: Dependency Update
about: Template para PRs que atualizam dependências
title: '[DEPENDENCY] '
labels: dependency, dependencies
assignees: onixaeroporto, reeseae64
---

## 📦 Tipo de Atualização

- [ ] Adicionar nova dependência
- [ ] Atualizar dependência existente
- [ ] Remover dependência
- [ ] Resolver conflito de dependências
- [ ] Atualizar dependência de segurança
- [ ] Atualização de versão crítica

## 📋 Issue Relacionada

- Resolve #
- Relacionado a #
- Fecha #

## 📦 Dependências Afetadas

Liste as dependências:

### Novas Dependências
- `package-name`: `versão` - [razão]

### Atualizações
- `package-name`: `versão-antiga` → `versão-nova`

### Remoções
- `package-name`: `versão` - [razão]

## 🎯 Motivo

Por que esta mudança nas dependências é necessária?

## ✅ Checklist

### Dependências
- [ ] Dependência testada localmente
- [ ] Versão verificada e compatível
- [ ] Breaking changes identificados
- [ ] Conflitos de dependências resolvidos
- [ ] Vulnerabilidades verificadas
- [ ] Licenças verificadas

### Código
- [ ] Código atualizado para compatibilidade
- [ ] Imports atualizados (se necessário)
- [ ] APIs deprecadas substituídas
- [ ] Testes atualizados

### Testes
- [ ] Testes passam localmente
- [ ] Testes de integração passam
- [ ] Testes E2E passam (se aplicável)
- [ ] Regressões testadas

### Build
- [ ] Build passa localmente
- [ ] Build passa no CI
- [ ] Sem erros de compatibilidade

### Documentação
- [ ] Changelog atualizado
- [ ] Documentação atualizada (se necessário)
- [ ] Notas de migração adicionadas (se necessário)

## 🔄 Breaking Changes

- [ ] Esta atualização introduz breaking changes
- [ ] Esta atualização NÃO introduz breaking changes

Se há breaking changes:

### O que mudou?

### Como migrar?

### Compatibilidade
- Versão mínima suportada: [ex: Node 18.x]
- Versões testadas: [lista]

## 📊 Impacto

### Arquivos Afetados
Liste arquivos principais afetados:

- `arquivo1.js` - [descrição]
- `arquivo2.js` - [descrição]

### Funcionalidades Afetadas
- [ ] Nenhuma mudança funcional
- [ ] Funcionalidades melhoradas
- [ ] Funcionalidades alteradas: [descrever]

## 🧪 Como Testar

Descreva como validar a atualização:

1. Instale dependências: `npm install` ou `yarn install`
2. Execute testes: `npm test`
3. Teste funcionalidade X: `...`
4. Verifique build: `npm run build`

## ⚠️ Riscos

Liste riscos potenciais:

- Risco 1: [mitigação]
- Risco 2: [mitigação]

## 🔒 Segurança

- [ ] Vulnerabilidades conhecidas verificadas
- [ ] Dependências de segurança atualizadas
- [ ] Auditoria de segurança realizada (se necessário)

## 📝 Notas Adicionais

Adicione informações adicionais relevantes sobre a atualização de dependências.

