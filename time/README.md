# Vrijeme i kalendar (Time & Calendar)

5 datasets — 1,247 records

> Browse at [listbase.org/hr/time/](https://listbase.org/hr/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Državni praznici i blagdani Republike Hrvatske (1992–2030)](hr-drzavni-praznici-blagdani.json) | 503 | 245 KB | [CSV](hr-drzavni-praznici-blagdani_HR.csv) | [Excel](hr-drzavni-praznici-blagdani_HR.xlsx) | [View](https://listbase.org/hr/time/hr-drzavni-praznici-blagdani/) |
| [Državni praznici i blagdani Republike Hrvatske (1992–2030) — multilingual completos](hr-drzavni-praznici-blagdani-completos.json) | 503 | 165 KB | [CSV](hr-drzavni-praznici-blagdani-completos_HR.csv) | [Excel](hr-drzavni-praznici-blagdani-completos_HR.xlsx) | [View](https://listbase.org/hr/time/hr-drzavni-praznici-blagdani-completos/) |
| [Hrvatski državni blagdani — višejezični (openpotato)](hr-blagdani-multijezicni.json) | 144 | 69 KB | [CSV](hr-blagdani-multijezicni_HR.csv) | [Excel](hr-blagdani-multijezicni_HR.xlsx) | [View](https://listbase.org/hr/time/hr-blagdani-multijezicni/) |
| [Nazivi mjeseci po kalendarima (CLDR hrvatski)](hr-mjeseci-po-kalendarima.json) | 74 | 13 KB | [CSV](hr-mjeseci-po-kalendarima_HR.csv) | [Excel](hr-mjeseci-po-kalendarima_HR.xlsx) | [View](https://listbase.org/hr/time/hr-mjeseci-po-kalendarima/) |
| [Dani, kvartali, doba dana i ere — hrvatski nazivi (CLDR)](hr-dani-kvartali-ere.json) | 23 | 4 KB | [CSV](hr-dani-kvartali-ere_HR.csv) | [Excel](hr-dani-kvartali-ere_HR.xlsx) | [View](https://listbase.org/hr/time/hr-dani-kvartali-ere/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/time/hr-drzavni-praznici-blagdani.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/time/)
