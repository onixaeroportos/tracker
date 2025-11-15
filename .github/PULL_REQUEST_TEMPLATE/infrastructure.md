---
name: Infrastructure
about: Template para PRs de infraestrutura
title: '[INFRA] '
labels: infra, infrastructure
assignees: onixaeroporto, reeseae64
---

## 🏗️ Tipo de Mudança

- [ ] Configuração de ambiente
- [ ] Mudança no CI/CD
- [ ] Mudança no deploy
- [ ] Configuração de monitoramento
- [ ] Mudança na infraestrutura
- [ ] Atualização de build
- [ ] Configuração de containerização

## 📋 Issue Relacionada

- Resolve #
- Relacionado a #

## 🎯 Objetivo

Por que esta mudança na infraestrutura é necessária?

## 🔧 Mudanças Realizadas

Descreva as mudanças:

- Mudança 1
- Mudança 2
- Mudança 3

## 📄 Arquivos Modificados

Liste arquivos de configuração modificados:

- `.github/workflows/arquivo.yml`
- `Dockerfile`
- `docker-compose.yml`
- `config/arquivo.env`

## ✅ Checklist

### Configuração
- [ ] Configuração testada localmente
- [ ] Configuração validada em staging
- [ ] Variáveis de ambiente documentadas
- [ ] Secrets gerenciados corretamente

### CI/CD
- [ ] Pipeline testado
- [ ] Build passa no CI
- [ ] Testes automatizados passam
- [ ] Deploy testado em staging

### Infraestrutura
- [ ] Mudanças de infraestrutura documentadas
- [ ] Rollback planejado
- [ ] Monitoramento configurado
- [ ] Alertas configurados (se necessário)

### Segurança
- [ ] Credenciais protegidas
- [ ] Permissões verificadas
- [ ] Vulnerabilidades verificadas

### Documentação
- [ ] Documentação atualizada
- [ ] Runbooks atualizados (se necessário)
- [ ] README atualizado (se necessário)

## 🔄 Impacto

### Ambientes Afetados
- [ ] Desenvolvimento
- [ ] Staging
- [ ] Produção

### Serviços Afetados
Liste serviços ou componentes afetados:

- Serviço 1
- Serviço 2

## 🧪 Como Testar

Descreva como validar as mudanças:

1. Teste localmente: `...`
2. Verifique CI: `...`
3. Teste deploy em staging: `...`
4. Valide monitoramento: `...`

## 🚨 Rollback Plan

Se necessário, descreva o plano de rollback:

1. Passo 1
2. Passo 2
3. Passo 3

## 📊 Monitoramento

Quais métricas devem ser monitoradas após o deploy:

- Métrica 1: [valor esperado]
- Métrica 2: [valor esperado]

## ⚠️ Riscos

Liste riscos potenciais:

- Risco 1: [mitigação]
- Risco 2: [mitigação]

## 🔐 Aprovações Necessárias

- [ ] Aprovação de infraestrutura: @mention
- [ ] Aprovação de DevOps: @mention
- [ ] Aprovação técnica: @mention

## 📝 Notas Adicionais

Adicione informações adicionais relevantes sobre as mudanças de infraestrutura.

