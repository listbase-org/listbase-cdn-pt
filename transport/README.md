# Transporte (Transport)

10 datasets — 6,858 records

> Browse at [listbase.org/pt/transport/](https://listbase.org/pt/transport/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Códigos UN/LOCODE — Brasil (portos, aeroportos, terminais)](pt-unlocode-brasil.json) | 5,635 | 3326 KB | [CSV](pt-unlocode-brasil_PT.csv) | [Excel](pt-unlocode-brasil_PT.xlsx) | [View](https://listbase.org/pt/transport/pt-unlocode-brasil/) |
| [Códigos UN/LOCODE — Portugal (portos, aeroportos, terminais)](pt-unlocode-portugal.json) | 950 | 624 KB | [CSV](pt-unlocode-portugal_PT.csv) | [Excel](pt-unlocode-portugal_PT.xlsx) | [View](https://listbase.org/pt/transport/pt-unlocode-portugal/) |
| [Estações do Metrô de São Paulo (Linhas 1, 2, 3, 4, 5, 6, 15, 17)](pt-metro-sp-estacoes.json) | 145 | 81 KB | [CSV](pt-metro-sp-estacoes_PT.csv) | [Excel](pt-metro-sp-estacoes_PT.xlsx) | [View](https://listbase.org/pt/transport/pt-metro-sp-estacoes/) |
| [Estações da Linha 2-Verde — Metrô de São Paulo](pt-metro-sp-linha-2-verde-estacoes.json) | 26 | 17 KB | [CSV](pt-metro-sp-linha-2-verde-estacoes_PT.csv) | [Excel](pt-metro-sp-linha-2-verde-estacoes_PT.xlsx) | [View](https://listbase.org/pt/transport/pt-metro-sp-linha-2-verde-estacoes/) |
| [Estações da Linha 1-Azul — Metrô de São Paulo](pt-metro-sp-linha-1-azul-estacoes.json) | 23 | 16 KB | [CSV](pt-metro-sp-linha-1-azul-estacoes_PT.csv) | [Excel](pt-metro-sp-linha-1-azul-estacoes_PT.xlsx) | [View](https://listbase.org/pt/transport/pt-metro-sp-linha-1-azul-estacoes/) |
| [Estações da Linha 15-Prata — Metrô de São Paulo](pt-metro-sp-linha-15-prata-estacoes.json) | 18 | 11 KB | [CSV](pt-metro-sp-linha-15-prata-estacoes_PT.csv) | [Excel](pt-metro-sp-linha-15-prata-estacoes_PT.xlsx) | [View](https://listbase.org/pt/transport/pt-metro-sp-linha-15-prata-estacoes/) |
| [Estações da Linha 3-Vermelha — Metrô de São Paulo](pt-metro-sp-linha-3-vermelha-estacoes.json) | 18 | 14 KB | [CSV](pt-metro-sp-linha-3-vermelha-estacoes_PT.csv) | [Excel](pt-metro-sp-linha-3-vermelha-estacoes_PT.xlsx) | [View](https://listbase.org/pt/transport/pt-metro-sp-linha-3-vermelha-estacoes/) |
| [Estações da Linha 5-Lilás — Metrô de São Paulo](pt-metro-sp-linha-5-lilas-estacoes.json) | 17 | 12 KB | [CSV](pt-metro-sp-linha-5-lilas-estacoes_PT.csv) | [Excel](pt-metro-sp-linha-5-lilas-estacoes_PT.xlsx) | [View](https://listbase.org/pt/transport/pt-metro-sp-linha-5-lilas-estacoes/) |
| [Estações da Linha 6-Laranja — Metrô de São Paulo](pt-metro-sp-linha-6-laranja-estacoes.json) | 15 | 10 KB | [CSV](pt-metro-sp-linha-6-laranja-estacoes_PT.csv) | [Excel](pt-metro-sp-linha-6-laranja-estacoes_PT.xlsx) | [View](https://listbase.org/pt/transport/pt-metro-sp-linha-6-laranja-estacoes/) |
| [Estações da Linha 4-Amarela — Metrô de São Paulo](pt-metro-sp-linha-4-amarela-estacoes.json) | 11 | 9 KB | [CSV](pt-metro-sp-linha-4-amarela-estacoes_PT.csv) | [Excel](pt-metro-sp-linha-4-amarela-estacoes_PT.xlsx) | [View](https://listbase.org/pt/transport/pt-metro-sp-linha-4-amarela-estacoes/) |

## Quick Start

```bash
# List all transport datasets
curl https://cdn.pt.listbase.org/index.json | jq '.datasets[] | select(.category=="transport") | .id'

# Fetch a dataset
curl https://cdn.pt.listbase.org/transport/pt-unlocode-brasil.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pt/transport/)
