# Jezik (Language)

2 datasets — 776 records

> Browse at [listbase.org/hr/language/](https://listbase.org/hr/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Jezici svijeta](hr-jezici.json) | 609 | 58 KB | [CSV](hr-jezici_HR.csv) | [Excel](hr-jezici_HR.xlsx) | [View](https://listbase.org/hr/language/hr-jezici/) |
| [Svjetska pisma (ISO 15924 / CLDR hrvatski)](hr-pisma.json) | 167 | 15 KB | [CSV](hr-pisma_HR.csv) | [Excel](hr-pisma_HR.xlsx) | [View](https://listbase.org/hr/language/hr-pisma/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/language/hr-jezici.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/language/)
