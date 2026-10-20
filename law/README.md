# Pravo (Law)

1 datasets — 327 records

> Browse at [listbase.org/hr/law/](https://listbase.org/hr/law/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Javni bilježnici u Republici Hrvatskoj](hr-javni-biljeznici.json) | 327 | 164 KB | [CSV](hr-javni-biljeznici_HR.csv) | [Excel](hr-javni-biljeznici_HR.xlsx) | [View](https://listbase.org/hr/law/hr-javni-biljeznici/) |

## Quick Start

```bash
# List all law datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="law") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/law/hr-javni-biljeznici.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/law/)
