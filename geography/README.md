# Geografia (Geography)

11 datasets — 27,396 records

> Browse at [listbase.org/pt/geography/](https://listbase.org/pt/geography/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Nomes femininos mais populares no Brasil (IBGE 2010)](pt-nomes-femininos-brasil-ibge.json) | 10,000 | 1653 KB | [CSV](pt-nomes-femininos-brasil-ibge_PT.csv) | [Excel](pt-nomes-femininos-brasil-ibge_PT.xlsx) | [View](https://listbase.org/pt/geography/pt-nomes-femininos-brasil-ibge/) |
| [Nomes masculinos mais populares no Brasil (IBGE 2010)](pt-nomes-masculinos-brasil-ibge.json) | 10,000 | 1650 KB | [CSV](pt-nomes-masculinos-brasil-ibge_PT.csv) | [Excel](pt-nomes-masculinos-brasil-ibge_PT.xlsx) | [View](https://listbase.org/pt/geography/pt-nomes-masculinos-brasil-ibge/) |
| [Municípios do Brasil — 5.571 municípios brasileiros (todas as UFs)](pt-municipios.json) | 5,571 | 2359 KB | [CSV](pt-municipios_PT.csv) | [Excel](pt-municipios_PT.xlsx) | [View](https://listbase.org/pt/geography/pt-municipios/) |
| [Cachoeiras e corredeiras em Portugal e Brasil](pt-cachoeiras.json) | 1,466 | 893 KB | [CSV](pt-cachoeiras_PT.csv) | [Excel](pt-cachoeiras_PT.xlsx) | [View](https://listbase.org/pt/geography/pt-cachoeiras/) |
| [Estacoes ferroviarias de Portugal](pt-estacoes-ferroviarias.json) | 187 | 78 KB | [CSV](pt-estacoes-ferroviarias_PT.csv) | [Excel](pt-estacoes-ferroviarias_PT.xlsx) | [View](https://listbase.org/pt/geography/pt-estacoes-ferroviarias/) |
| [Apelidos mais frequentes em Portugal (Popular Portuguese Surnames)](pt-apelidos-portugal.json) | 50 | 10 KB | [CSV](pt-apelidos-portugal_PT.csv) | [Excel](pt-apelidos-portugal_PT.xlsx) | [View](https://listbase.org/pt/geography/pt-apelidos-portugal/) |
| [Nomes mais populares no Brasil (Popular Brazilian Forenames)](pt-nomes-brasil.json) | 40 | 8 KB | [CSV](pt-nomes-brasil_PT.csv) | [Excel](pt-nomes-brasil_PT.xlsx) | [View](https://listbase.org/pt/geography/pt-nomes-brasil/) |
| [Sobrenomes mais frequentes no Brasil (Popular Brazilian Surnames)](pt-sobrenomes-brasil.json) | 30 | 7 KB | [CSV](pt-sobrenomes-brasil_PT.csv) | [Excel](pt-sobrenomes-brasil_PT.xlsx) | [View](https://listbase.org/pt/geography/pt-sobrenomes-brasil/) |
| [Capitais do Brasil — 27 capitais dos estados e do Distrito Federal](pt-capitais.json) | 27 | 14 KB | [CSV](pt-capitais_PT.csv) | [Excel](pt-capitais_PT.xlsx) | [View](https://listbase.org/pt/geography/pt-capitais/) |
| [Nomes próprios mais populares em Portugal (Popular Portuguese Forenames)](pt-nomes-portugal.json) | 20 | 5 KB | [CSV](pt-nomes-portugal_PT.csv) | [Excel](pt-nomes-portugal_PT.xlsx) | [View](https://listbase.org/pt/geography/pt-nomes-portugal/) |
| [Regiões do Brasil — 5 regiões geográficas IBGE](pt-regioes.json) | 5 | 5 KB | [CSV](pt-regioes_PT.csv) | [Excel](pt-regioes_PT.xlsx) | [View](https://listbase.org/pt/geography/pt-regioes/) |

## Quick Start

```bash
# List all geography datasets
curl https://cdn.pt.listbase.org/index.json | jq '.datasets[] | select(.category=="geography") | .id'

# Fetch a dataset
curl https://cdn.pt.listbase.org/geography/pt-nomes-femininos-brasil-ibge.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pt/geography/)
