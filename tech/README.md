# Tehnologija (Technology)

11 datasets — 2,286 records

> Browse at [listbase.org/hr/tech/](https://listbase.org/hr/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Emoji — hrvatski nazivi (CLDR)](hr-emoji-nazivi.json) | 1,966 | 316 KB | [CSV](hr-emoji-nazivi_HR.csv) | [Excel](hr-emoji-nazivi_HR.xlsx) | [View](https://listbase.org/hr/tech/hr-emoji-nazivi/) |
| [Vremenske zone svijeta (IANA / CLDR hrvatski)](hr-vremenske-zone.json) | 160 | 28 KB | [CSV](hr-vremenske-zone_HR.csv) | [Excel](hr-vremenske-zone_HR.xlsx) | [View](https://listbase.org/hr/tech/hr-vremenske-zone/) |
| [Vremenske zone — America (51)](hr-vremenske-zone-america.json) | 51 | 10 KB | [CSV](hr-vremenske-zone-america_HR.csv) | [Excel](hr-vremenske-zone-america_HR.xlsx) | [View](https://listbase.org/hr/tech/hr-vremenske-zone-america/) |
| [Vremenske zone — Asia (45)](hr-vremenske-zone-asia.json) | 45 | 8 KB | [CSV](hr-vremenske-zone-asia_HR.csv) | [Excel](hr-vremenske-zone-asia_HR.xlsx) | [View](https://listbase.org/hr/tech/hr-vremenske-zone-asia/) |
| [Vremenske zone — Europe (31)](hr-vremenske-zone-europe.json) | 31 | 6 KB | [CSV](hr-vremenske-zone-europe_HR.csv) | [Excel](hr-vremenske-zone-europe_HR.xlsx) | [View](https://listbase.org/hr/tech/hr-vremenske-zone-europe/) |
| [Vremenske zone — Africa (9)](hr-vremenske-zone-africa.json) | 9 | 3 KB | [CSV](hr-vremenske-zone-africa_HR.csv) | [Excel](hr-vremenske-zone-africa_HR.xlsx) | [View](https://listbase.org/hr/tech/hr-vremenske-zone-africa/) |
| [Vremenske zone — Pacific (9)](hr-vremenske-zone-pacific.json) | 9 | 3 KB | [CSV](hr-vremenske-zone-pacific_HR.csv) | [Excel](hr-vremenske-zone-pacific_HR.xlsx) | [View](https://listbase.org/hr/tech/hr-vremenske-zone-pacific/) |
| [Vremenske zone — Atlantic (6)](hr-vremenske-zone-atlantic.json) | 6 | 2 KB | [CSV](hr-vremenske-zone-atlantic_HR.csv) | [Excel](hr-vremenske-zone-atlantic_HR.xlsx) | [View](https://listbase.org/hr/tech/hr-vremenske-zone-atlantic/) |
| [Vremenske zone — Indian (5)](hr-vremenske-zone-indian.json) | 5 | 2 KB | [CSV](hr-vremenske-zone-indian_HR.csv) | [Excel](hr-vremenske-zone-indian_HR.xlsx) | [View](https://listbase.org/hr/tech/hr-vremenske-zone-indian/) |
| [Vremenske zone — Antarctica (2)](hr-vremenske-zone-antarctica.json) | 2 | 2 KB | [CSV](hr-vremenske-zone-antarctica_HR.csv) | [Excel](hr-vremenske-zone-antarctica_HR.xlsx) | [View](https://listbase.org/hr/tech/hr-vremenske-zone-antarctica/) |
| [Vremenske zone — Etc (2)](hr-vremenske-zone-etc.json) | 2 | 2 KB | [CSV](hr-vremenske-zone-etc_HR.csv) | [Excel](hr-vremenske-zone-etc_HR.xlsx) | [View](https://listbase.org/hr/tech/hr-vremenske-zone-etc/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/tech/hr-emoji-nazivi.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/tech/)
