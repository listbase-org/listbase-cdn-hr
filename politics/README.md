# Politika (Politics)

3 datasets — 12,494 records

> Browse at [listbase.org/hr/politics/](https://listbase.org/hr/politics/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Funkcije u političkim strankama u Republici Hrvatskoj (1990–2015)](hr-politicke-stranke-funkcije.json) | 6,133 | 1346 KB | [CSV](hr-politicke-stranke-funkcije_HR.csv) | [Excel](hr-politicke-stranke-funkcije_HR.xlsx) | [View](https://listbase.org/hr/politics/hr-politicke-stranke-funkcije/) |
| [Tijela javne vlasti u Republici Hrvatskoj](hr-tijela-javne-vlasti.json) | 5,755 | 4001 KB | [CSV](hr-tijela-javne-vlasti_HR.csv) | [Excel](hr-tijela-javne-vlasti_HR.xlsx) | [View](https://listbase.org/hr/politics/hr-tijela-javne-vlasti/) |
| [Vladini uredi](hr-vladini-uredi.json) | 606 | 70 KB | [CSV](hr-vladini-uredi_HR.csv) | [Excel](hr-vladini-uredi_HR.xlsx) | [View](https://listbase.org/hr/politics/hr-vladini-uredi/) |

## Quick Start

```bash
# List all politics datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="politics") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/politics/hr-politicke-stranke-funkcije.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/politics/)
