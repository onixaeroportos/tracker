---
name: Security Fix
about: Template para PRs relacionados a segurança
title: '[SECURITY] '
labels: security, vulnerability
assignees: onixaeroporto, reeseae64
---

## 🔒 Tipo de Correção

- [ ] Correção de vulnerabilidade
- [ ] Melhoria de segurança
- [ ] Implementação de auditoria de segurança
- [ ] Correção de permissões/ACL
- [ ] Atualização de dependência vulnerável

## 📋 Issue Relacionada

- Resolve #
- Relacionado a #

## 🚨 Severidade

- [ ] Crítica
- [ ] Alta
- [ ] Média
- [ ] Baixa

## 🔍 Vulnerabilidade Corrigida

Descreva a vulnerabilidade ou problema de segurança que foi corrigido.

**NOTA:** Se a vulnerabilidade ainda não foi divulgada publicamente, mantenha detalhes sensíveis fora deste PR até que seja seguro divulgar.

## 🔧 Solução Implementada

Descreva como o problema de segurança foi corrigido ou mitigado.

## 🛡️ Medidas de Segurança Adicionadas

Liste medidas de segurança implementadas:

- Medida 1
- Medida 2
- Medida 3

## 🧪 Como Testar

Descreva como validar a correção (sem expor vulnerabilidades):

1. Faça '...'
2. Verifique que '...'
3. Confirme que '...'

## ✅ Checklist

### Segurança
- [ ] Vulnerabilidade corrigida
- [ ] Testes de segurança realizados
- [ ] Validações de entrada implementadas
- [ ] Dados sensíveis protegidos
- [ ] Permissões/ACL verificadas
- [ ] Logs de segurança implementados (se aplicável)
- [ ] Criptografia verificada (se aplicável)

### Código
- [ ] Código revisado por perspectiva de segurança
- [ ] Sem introdução de novas vulnerabilidades
- [ ] Padrões de segurança seguidos

### Testes
- [ ] Testes de segurança adicionados
- [ ] Testes de penetração realizados (se aplicável)
- [ ] Regressões de segurança testadas
- [ ] Todos os testes passam

### Documentação
- [ ] Documentação de segurança atualizada
- [ ] Aviso de segurança preparado (se necessário)
- [ ] Migração documentada (se aplicável)

### Auditoria
- [ ] Auditoria de segurança realizada
- [ ] Aprovação de segurança obtida
- [ ] Stakeholders notificados (se crítico)

## 🔄 Impacto

### Compatibilidade
- [ ] Sem impacto em compatibilidade
- [ ] Requer atualização de clientes: [descrever]

### Performance
- [ ] Sem impacto em performance
- [ ] Impacto em performance: [descrever]

### Usuários
- [ ] Transparente para usuários
- [ ] Requer ação dos usuários: [descrever]

## 🚫 Breaking Changes

- [ ] Esta correção introduz breaking changes
- [ ] Esta correção NÃO introduz breaking changes

Se há breaking changes, descreva:

### O que mudou?

### Como migrar?

## 📅 Disclosure

- [ ] Vulnerabilidade já divulgada publicamente
- [ ] Vulnerabilidade ainda privada
- [ ] Data de disclosure planejada: [data]
- [ ] Aviso de segurança: [link]

## 🔐 Aprovações Necessárias

- [ ] Aprovação de segurança: @mention
- [ ] Aprovação técnica: @mention
- [ ] Aprovação de produto: @mention

## ⚠️ Nota Importante

**Este PR não deve ser mergeado até que todas as aprovações de segurança sejam obtidas e, se necessário, um aviso de segurança seja publicado.**

## 📝 Notas Adicionais

Adicione informações adicionais relevantes sobre a correção de segurança.

