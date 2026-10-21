# Meio ambiente (Environment)

4 datasets — 527 records

> Browse at [listbase.org/pt/environment/](https://listbase.org/pt/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Centrais elétricas de Portugal](pt-centrais-eletricas-portugal.json) | 505 | 263 KB | [CSV](pt-centrais-eletricas-portugal_PT.csv) | [Excel](pt-centrais-eletricas-portugal_PT.xlsx) | [View](https://listbase.org/pt/environment/pt-centrais-eletricas-portugal/) |
| [Unidades de medida — categoria 'energy' (14)](pt-unidades-medida-energy.json) | 14 | 5 KB | [CSV](pt-unidades-medida-energy_PT.csv) | [Excel](pt-unidades-medida-energy_PT.xlsx) | [View](https://listbase.org/pt/environment/pt-unidades-medida-energy/) |
| [Unidades de medida — categoria 'temperature' (5)](pt-unidades-medida-temperature.json) | 5 | 3 KB | [CSV](pt-unidades-medida-temperature_PT.csv) | [Excel](pt-unidades-medida-temperature_PT.xlsx) | [View](https://listbase.org/pt/environment/pt-unidades-medida-temperature/) |
| [Usinas nucleares no Brasil](pt-usinas-nucleares.json) | 3 | 4 KB | [CSV](pt-usinas-nucleares_PT.csv) | [Excel](pt-usinas-nucleares_PT.xlsx) | [View](https://listbase.org/pt/environment/pt-usinas-nucleares/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.pt.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.pt.listbase.org/environment/pt-centrais-eletricas-portugal.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pt/environment/)
