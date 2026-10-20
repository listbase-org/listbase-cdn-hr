# Zdravlje (Health)

7 datasets — 1,675 records

> Browse at [listbase.org/hr/health/](https://listbase.org/hr/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Liječničke ordinacije](hr-lijecnicke-ordinacije.json) | 469 | 52 KB | [CSV](hr-lijecnicke-ordinacije_HR.csv) | [Excel](hr-lijecnicke-ordinacije_HR.xlsx) | [View](https://listbase.org/hr/health/hr-lijecnicke-ordinacije/) |
| [Poliklinike](hr-poliklinike.json) | 304 | 34 KB | [CSV](hr-poliklinike_HR.csv) | [Excel](hr-poliklinike_HR.xlsx) | [View](https://listbase.org/hr/health/hr-poliklinike/) |
| [Optike](hr-optike.json) | 236 | 24 KB | [CSV](hr-optike_HR.csv) | [Excel](hr-optike_HR.xlsx) | [View](https://listbase.org/hr/health/hr-optike/) |
| [Stomatološke ordinacije](hr-stomatoloske-ordinacije.json) | 216 | 25 KB | [CSV](hr-stomatoloske-ordinacije_HR.csv) | [Excel](hr-stomatoloske-ordinacije_HR.xlsx) | [View](https://listbase.org/hr/health/hr-stomatoloske-ordinacije/) |
| [Socijalne ustanove](hr-socijalne-ustanove.json) | 205 | 25 KB | [CSV](hr-socijalne-ustanove_HR.csv) | [Excel](hr-socijalne-ustanove_HR.xlsx) | [View](https://listbase.org/hr/health/hr-socijalne-ustanove/) |
| [Veterinarske ambulante](hr-veterinarske-ambulante.json) | 159 | 19 KB | [CSV](hr-veterinarske-ambulante_HR.csv) | [Excel](hr-veterinarske-ambulante_HR.xlsx) | [View](https://listbase.org/hr/health/hr-veterinarske-ambulante/) |
| [Bolnice](hr-bolnice.json) | 86 | 12 KB | [CSV](hr-bolnice_HR.csv) | [Excel](hr-bolnice_HR.xlsx) | [View](https://listbase.org/hr/health/hr-bolnice/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/health/hr-lijecnicke-ordinacije.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/health/)
