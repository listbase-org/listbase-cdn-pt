# Educação (Education)

2 datasets — 255 records

> Browse at [listbase.org/pt/education/](https://listbase.org/pt/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Brazil — Universidades (Universities)](pt-universidades-brasil.json) | 189 | 54 KB | [CSV](pt-universidades-brasil_PT.csv) | [Excel](pt-universidades-brasil_PT.xlsx) | [View](https://listbase.org/pt/education/pt-universidades-brasil/) |
| [Portugal — Universidades (Universities)](pt-universidades-portugal.json) | 66 | 20 KB | [CSV](pt-universidades-portugal_PT.csv) | [Excel](pt-universidades-portugal_PT.xlsx) | [View](https://listbase.org/pt/education/pt-universidades-portugal/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.pt.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.pt.listbase.org/education/pt-universidades-brasil.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pt/education/)
