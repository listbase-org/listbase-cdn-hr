# Zabava (Entertainment)

1 datasets — 139 records

> Browse at [listbase.org/hr/entertainment/](https://listbase.org/hr/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Knjižare](hr-knjizare.json) | 139 | 15 KB | [CSV](hr-knjizare_HR.csv) | [Excel](hr-knjizare_HR.xlsx) | [View](https://listbase.org/hr/entertainment/hr-knjizare/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/entertainment/hr-knjizare.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/entertainment/)
