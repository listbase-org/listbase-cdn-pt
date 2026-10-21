# Cultura e religião (Culture & Religion)

1 datasets — 17 records

> Browse at [listbase.org/pt/culture/](https://listbase.org/pt/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Património Mundial da UNESCO em Portugal](pt-patrimonio-mundial-unesco.json) | 17 | 18 KB | [CSV](pt-patrimonio-mundial-unesco_PT.csv) | [Excel](pt-patrimonio-mundial-unesco_PT.xlsx) | [View](https://listbase.org/pt/culture/pt-patrimonio-mundial-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.pt.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.pt.listbase.org/culture/pt-patrimonio-mundial-unesco.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pt/culture/)
