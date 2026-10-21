# Esportes (Sports)

2 datasets — 56 records

> Browse at [listbase.org/pt/sports/](https://listbase.org/pt/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Canais de televisão de esportes do Brasil](pt-br-canais-tv-desporto.json) | 42 | 17 KB | [CSV](pt-br-canais-tv-desporto_PT.csv) | [Excel](pt-br-canais-tv-desporto_PT.xlsx) | [View](https://listbase.org/pt/sports/pt-br-canais-tv-desporto/) |
| [Canais de televisão de desporto de Portugal](pt-canais-tv-desporto.json) | 14 | 7 KB | [CSV](pt-canais-tv-desporto_PT.csv) | [Excel](pt-canais-tv-desporto_PT.xlsx) | [View](https://listbase.org/pt/sports/pt-canais-tv-desporto/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.pt.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.pt.listbase.org/sports/pt-br-canais-tv-desporto.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pt/sports/)
