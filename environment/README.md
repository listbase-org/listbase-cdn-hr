# Okoliš (Environment)

3 datasets — 136 records

> Browse at [listbase.org/hr/environment/](https://listbase.org/hr/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Elektrane u Hrvatskoj](hr-elektrane.json) | 117 | 62 KB | [CSV](hr-elektrane_HR.csv) | [Excel](hr-elektrane_HR.xlsx) | [View](https://listbase.org/hr/environment/hr-elektrane/) |
| [Mjerne jedinice — kategorija 'energy' (14)](hr-mjerne-jedinice-energy.json) | 14 | 5 KB | [CSV](hr-mjerne-jedinice-energy_HR.csv) | [Excel](hr-mjerne-jedinice-energy_HR.xlsx) | [View](https://listbase.org/hr/environment/hr-mjerne-jedinice-energy/) |
| [Mjerne jedinice — kategorija 'temperature' (5)](hr-mjerne-jedinice-temperature.json) | 5 | 3 KB | [CSV](hr-mjerne-jedinice-temperature_HR.csv) | [Excel](hr-mjerne-jedinice-temperature_HR.xlsx) | [View](https://listbase.org/hr/environment/hr-mjerne-jedinice-temperature/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/environment/hr-elektrane.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/environment/)
