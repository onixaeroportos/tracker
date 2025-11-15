---
name: Performance Optimization
about: Template para PRs de otimização de performance
title: '[PERFORMANCE] '
labels: optimization, performance
assignees: onixaeroporto, reeseae64
---

## ⚡ Tipo de Otimização

- [ ] Otimização geral de performance
- [ ] Otimização de consultas de banco
- [ ] Otimização de memória
- [ ] Otimização de tempo de carregamento
- [ ] Otimização de algoritmo
- [ ] Otimização de cache
- [ ] Otimização de build/CI
- [ ] Otimização de recursos

## 📋 Issue Relacionada

- Resolve #
- Relacionado a #
- Resolve problema de: [slow-query, memory-issue, etc.]

## 🎯 Problema Identificado

Descreva o problema de performance que foi identificado.

## 🔧 Solução Implementada

Descreva a otimização implementada.

## 📊 Métricas

### Antes da Otimização
- Tempo de resposta: [ex: 2.5s]
- Uso de memória: [ex: 500MB]
- CPU: [ex: 80%]
- Throughput: [ex: 100 req/s]
- Query time: [ex: 800ms]
- Tempo de build: [ex: 5min]

### Depois da Otimização
- Tempo de resposta: [ex: 500ms]
- Uso de memória: [ex: 200MB]
- CPU: [ex: 50%]
- Throughput: [ex: 500 req/s]
- Query time: [ex: 100ms]
- Tempo de build: [ex: 2min]

### Melhoria
- Tempo de resposta: ⬇️ [ex: 80% mais rápido]
- Uso de memória: ⬇️ [ex: 60% menos]
- CPU: ⬇️ [ex: 37.5% menos]
- Throughput: ⬆️ [ex: 5x maior]
- Query time: ⬇️ [ex: 87.5% mais rápido]

## 📈 Benchmark

Se disponível, adicione resultados de benchmark:

```resultados
Resultados do benchmark aqui
```

## ✅ Checklist

### Otimização
- [ ] Performance melhorada
- [ ] Métricas coletadas e documentadas
- [ ] Benchmark realizado
- [ ] Melhoria validada em ambiente de staging/produção

### Código
- [ ] Código otimizado mantém legibilidade
- [ ] Padrões do projeto seguidos
- [ ] Complexidade gerenciada

### Testes
- [ ] Testes de performance adicionados
- [ ] Testes de carga realizados (se aplicável)
- [ ] Testes de stress realizados (se aplicável)
- [ ] Testes funcionais ainda passam
- [ ] Sem regressões introduzidas

### Impacto
- [ ] Sem impacto em funcionalidade
- [ ] Sem impacto negativo em outros aspectos
- [ ] Trade-offs documentados (se houver)

## 🔍 Áreas Otimizadas

Marque as áreas otimizadas:

- [ ] Backend
- [ ] Frontend
- [ ] Banco de dados
- [ ] API
- [ ] Cache
- [ ] Build/CI
- [ ] Infraestrutura
- [ ] Rede

## 🧪 Como Testar

Descreva como validar a melhoria de performance:

1. Execute benchmark: `...`
2. Monitore métricas: `...`
3. Compare com baseline: `...`
4. Valide em produção: `...`

## ⚠️ Trade-offs

Se houver trade-offs, documente-os:

- Trade-off 1: [descrição e justificativa]
- Trade-off 2: [descrição e justificativa]

## 🔄 Impacto

### Funcionalidade
- [ ] Sem mudança funcional
- [ ] Mudança funcional mínima: [descrever]

### Compatibilidade
- [ ] Sem impacto em compatibilidade
- [ ] Requer mudanças em clientes: [descrever]

### Infraestrutura
- [ ] Sem mudanças na infraestrutura
- [ ] Requer mudanças na infraestrutura: [descrever]

## 📝 Notas Adicionais

Adicione informações adicionais relevantes sobre a otimização.

