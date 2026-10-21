# Finanças e comércio (Finance & Trade)

2 datasets — 270 records

> Browse at [listbase.org/pt/finance/](https://listbase.org/pt/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Códigos SWIFT/BIC — Portugal](pt-swift-codigos.json) | 253 | 38 KB | [CSV](pt-swift-codigos_PT.csv) | [Excel](pt-swift-codigos_PT.xlsx) | [View](https://listbase.org/pt/finance/pt-swift-codigos/) |
| [Estações da Linha 17-Ouro — Metrô de São Paulo](pt-metro-sp-linha-17-ouro-estacoes.json) | 17 | 11 KB | [CSV](pt-metro-sp-linha-17-ouro-estacoes_PT.csv) | [Excel](pt-metro-sp-linha-17-ouro-estacoes_PT.xlsx) | [View](https://listbase.org/pt/finance/pt-metro-sp-linha-17-ouro-estacoes/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.pt.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.pt.listbase.org/finance/pt-swift-codigos.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pt/finance/)
