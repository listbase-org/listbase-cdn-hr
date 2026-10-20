# Društvo (Society)

1 datasets — 272 records

> Browse at [listbase.org/hr/society/](https://listbase.org/hr/society/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Policijske postaje](hr-policijske-postaje.json) | 272 | 33 KB | [CSV](hr-policijske-postaje_HR.csv) | [Excel](hr-policijske-postaje_HR.xlsx) | [View](https://listbase.org/hr/society/hr-policijske-postaje/) |

## Quick Start

```bash
# List all society datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="society") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/society/hr-policijske-postaje.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/society/)
