# Comida (Food & Nutrition)

2 datasets — 354 records

> Browse at [listbase.org/pt/food/](https://listbase.org/pt/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Restaurantes do Guia Michelin em Portugal](pt-restaurantes-michelin-portugal.json) | 206 | 276 KB | [CSV](pt-restaurantes-michelin-portugal_PT.csv) | [Excel](pt-restaurantes-michelin-portugal_PT.xlsx) | [View](https://listbase.org/pt/food/pt-restaurantes-michelin-portugal/) |
| [Restaurantes do Guia Michelin no Brasil](pt-restaurantes-michelin-brasil.json) | 148 | 211 KB | [CSV](pt-restaurantes-michelin-brasil_PT.csv) | [Excel](pt-restaurantes-michelin-brasil_PT.xlsx) | [View](https://listbase.org/pt/food/pt-restaurantes-michelin-brasil/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.pt.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.pt.listbase.org/food/pt-restaurantes-michelin-portugal.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pt/food/)
