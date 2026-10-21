# Tecnologia (Technology)

16 datasets — 3,407 records

> Browse at [listbase.org/pt/tech/](https://listbase.org/pt/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Emoji — nomes em português (CLDR)](pt-nomes-emoji.json) | 1,966 | 323 KB | [CSV](pt-nomes-emoji_PT.csv) | [Excel](pt-nomes-emoji_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-nomes-emoji/) |
| [Cartórios de Goiás (GO)](pt-cartorios-go.json) | 521 | 576 KB | [CSV](pt-cartorios-go_PT.csv) | [Excel](pt-cartorios-go_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-cartorios-go/) |
| [Fronteiras dos Municípios — Goiás (GO)](pt-br-goias-municipios-fronteiras.json) | 246 | 212 KB | [CSV](pt-br-goias-municipios-fronteiras_PT.csv) | [Excel](pt-br-goias-municipios-fronteiras_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-br-goias-municipios-fronteiras/) |
| [Municípios de Goiás (GO) — 246 municípios](pt-goias-municipios.json) | 246 | 107 KB | [CSV](pt-goias-municipios_PT.csv) | [Excel](pt-goias-municipios_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-goias-municipios/) |
| [Fusos horários do mundo (IANA / CLDR português)](pt-fusos-horarios.json) | 174 | 30 KB | [CSV](pt-fusos-horarios_PT.csv) | [Excel](pt-fusos-horarios_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-fusos-horarios/) |
| [Museus de Goiás (GO) — Cadastro Nacional de Museus / IBRAM](pt-goias-museus.json) | 70 | 141 KB | [CSV](pt-goias-museus_PT.csv) | [Excel](pt-goias-museus_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-goias-museus/) |
| [Fusos horários — America (58)](pt-fusos-horarios-america.json) | 58 | 11 KB | [CSV](pt-fusos-horarios-america_PT.csv) | [Excel](pt-fusos-horarios-america_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-fusos-horarios-america/) |
| [Fusos horários — Europe (35)](pt-fusos-horarios-europe.json) | 35 | 7 KB | [CSV](pt-fusos-horarios-europe_PT.csv) | [Excel](pt-fusos-horarios-europe_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-fusos-horarios-europe/) |
| [Fusos horários — Asia (34)](pt-fusos-horarios-asia.json) | 34 | 7 KB | [CSV](pt-fusos-horarios-asia_PT.csv) | [Excel](pt-fusos-horarios-asia_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-fusos-horarios-asia/) |
| [Fusos horários — Africa (18)](pt-fusos-horarios-africa.json) | 18 | 4 KB | [CSV](pt-fusos-horarios-africa_PT.csv) | [Excel](pt-fusos-horarios-africa_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-fusos-horarios-africa/) |
| [Fusos horários — Pacific (12)](pt-fusos-horarios-pacific.json) | 12 | 3 KB | [CSV](pt-fusos-horarios-pacific_PT.csv) | [Excel](pt-fusos-horarios-pacific_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-fusos-horarios-pacific/) |
| [Unidades de Conservação Federais — Goiás (GO)](pt-br-goias-unidades-conservacao.json) | 10 | 9 KB | [CSV](pt-br-goias-unidades-conservacao_PT.csv) | [Excel](pt-br-goias-unidades-conservacao_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-br-goias-unidades-conservacao/) |
| [Fusos horários — Atlantic (8)](pt-fusos-horarios-atlantic.json) | 8 | 3 KB | [CSV](pt-fusos-horarios-atlantic_PT.csv) | [Excel](pt-fusos-horarios-atlantic_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-fusos-horarios-atlantic/) |
| [Fusos horários — Indian (5)](pt-fusos-horarios-indian.json) | 5 | 2 KB | [CSV](pt-fusos-horarios-indian_PT.csv) | [Excel](pt-fusos-horarios-indian_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-fusos-horarios-indian/) |
| [Fusos horários — Antarctica (2)](pt-fusos-horarios-antarctica.json) | 2 | 2 KB | [CSV](pt-fusos-horarios-antarctica_PT.csv) | [Excel](pt-fusos-horarios-antarctica_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-fusos-horarios-antarctica/) |
| [Fusos horários — Etc (2)](pt-fusos-horarios-etc.json) | 2 | 2 KB | [CSV](pt-fusos-horarios-etc_PT.csv) | [Excel](pt-fusos-horarios-etc_PT.xlsx) | [View](https://listbase.org/pt/tech/pt-fusos-horarios-etc/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.pt.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.pt.listbase.org/tech/pt-nomes-emoji.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/pt/tech/)
