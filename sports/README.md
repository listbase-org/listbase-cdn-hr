# Sport (Sports)

1 datasets — 164 records

> Browse at [listbase.org/hr/sports/](https://listbase.org/hr/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Sportske trgovine](hr-sportske-trgovine.json) | 164 | 17 KB | [CSV](hr-sportske-trgovine_HR.csv) | [Excel](hr-sportske-trgovine_HR.xlsx) | [View](https://listbase.org/hr/sports/hr-sportske-trgovine/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/sports/hr-sportske-trgovine.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/sports/)
