# Hrana (Food & Nutrition)

6 datasets — 903 records

> Browse at [listbase.org/hr/food/](https://listbase.org/hr/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Pubovi](hr-pubovi.json) | 331 | 33 KB | [CSV](hr-pubovi_HR.csv) | [Excel](hr-pubovi_HR.xlsx) | [View](https://listbase.org/hr/food/hr-pubovi/) |
| [Sladoledarnice](hr-sladoledarnice.json) | 212 | 22 KB | [CSV](hr-sladoledarnice_HR.csv) | [Excel](hr-sladoledarnice_HR.xlsx) | [View](https://listbase.org/hr/food/hr-sladoledarnice/) |
| [Vinoteke](hr-vinoteke.json) | 142 | 15 KB | [CSV](hr-vinoteke_HR.csv) | [Excel](hr-vinoteke_HR.xlsx) | [View](https://listbase.org/hr/food/hr-vinoteke/) |
| [Slastičarnice](hr-slasticarnice.json) | 107 | 12 KB | [CSV](hr-slasticarnice_HR.csv) | [Excel](hr-slasticarnice_HR.xlsx) | [View](https://listbase.org/hr/food/hr-slasticarnice/) |
| [Michelin restorani u Hrvatskoj](hr-michelin-restorani.json) | 96 | 114 KB | [CSV](hr-michelin-restorani_HR.csv) | [Excel](hr-michelin-restorani_HR.xlsx) | [View](https://listbase.org/hr/food/hr-michelin-restorani/) |
| [Vegan restorani u Hrvatskoj](hr-vegan-restorani.json) | 15 | 13 KB | [CSV](hr-vegan-restorani_HR.csv) | [Excel](hr-vegan-restorani_HR.xlsx) | [View](https://listbase.org/hr/food/hr-vegan-restorani/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/food/hr-pubovi.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/food/)
