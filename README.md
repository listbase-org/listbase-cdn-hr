# ListBase CDN — Hrvatski (hr)

Open dataset collection for **Hrvatski** (Croatian).
416 datasets across 19 categories with 822,019 total records.

> Browse and download at [https://listbase.org/hr/](https://listbase.org/hr/)

## Categories

| Category | Datasets |
|----------|----------|
| [Kultura i religija (Culture & Religion)](culture/) | 14 |
| [Obrazovanje (Education)](education/) | 26 |
| [Zabava (Entertainment)](entertainment/) | 1 |
| [Okoliš (Environment)](environment/) | 3 |
| [Financije i trgovina (Finance & Trade)](finance/) | 8 |
| [Hrana (Food & Nutrition)](food/) | 6 |
| [Geografija (Geography)](geography/) | 17 |
| [Zdravlje (Health)](health/) | 7 |
| [Jezik (Language)](language/) | 2 |
| [Pravo (Law)](law/) | 1 |
| [Politika (Politics)](politics/) | 3 |
| [Referenca (Reference)](reference/) | 235 |
| [Društvo (Society)](society/) | 1 |
| [Sport (Sports)](sports/) | 1 |
| [Tehnologija (Technology)](tech/) | 11 |
| [Vrijeme i kalendar (Time & Calendar)](time/) | 5 |
| [Turizam (Tourism)](tourism/) | 13 |
| [Promet (Transport)](transport/) | 41 |
| [Jedinice i mjere (Units & Measurements)](units/) | 21 |

## Usage

### Browse on the web
Visit [listbase.org/hr/](https://listbase.org/hr/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.hr.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.hr.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.hr.listbase.org/geography/th-central-provinces_HR.xlsx
curl -O https://cdn.hr.listbase.org/geography/th-central-provinces_HR.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.hr.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.hr.listbase.org/geography/th-central-provinces.json');
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
│   ├── {dataset}_HR.csv   # CSV download
│   └── {dataset}_HR.xlsx  # Excel download
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
