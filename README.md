# ListBase CDN — Português (pt)

Open dataset collection for **Português** (Portuguese).
470 datasets across 15 categories with 737,911 total records.

> Browse and download at [https://listbase.org/pt/](https://listbase.org/pt/)

## Categories

| Category | Datasets |
|----------|----------|
| [Cultura e religião (Culture & Religion)](culture/) | 1 |
| [Educação (Education)](education/) | 2 |
| [Entretenimento (Entertainment)](entertainment/) | 28 |
| [Meio ambiente (Environment)](environment/) | 4 |
| [Finanças e comércio (Finance & Trade)](finance/) | 2 |
| [Comida (Food & Nutrition)](food/) | 2 |
| [Geografia (Geography)](geography/) | 11 |
| [Saúde (Health)](health/) | 27 |
| [Idioma (Language)](language/) | 1 |
| [Referência (Reference)](reference/) | 263 |
| [Esportes (Sports)](sports/) | 2 |
| [Tecnologia (Technology)](tech/) | 16 |
| [Tempo e calendário (Time & Calendar)](time/) | 80 |
| [Transporte (Transport)](transport/) | 10 |
| [Unidades e medidas (Units & Measurements)](units/) | 21 |

## Usage

### Browse on the web
Visit [listbase.org/pt/](https://listbase.org/pt/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.pt.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.pt.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.pt.listbase.org/geography/th-central-provinces_PT.xlsx
curl -O https://cdn.pt.listbase.org/geography/th-central-provinces_PT.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.pt.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.pt.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_PT.csv   # CSV download
│   └── {dataset}_PT.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
