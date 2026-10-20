# Kultura i religija (Culture & Religion)

14 datasets — 4,010 records

> Browse at [listbase.org/hr/culture/](https://listbase.org/hr/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Spomen-obilježja](hr-spomen-obiljezja.json) | 1,389 | 156 KB | [CSV](hr-spomen-obiljezja_HR.csv) | [Excel](hr-spomen-obiljezja_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-spomen-obiljezja/) |
| [Javne umjetnine](hr-javne-umjetnine.json) | 793 | 81 KB | [CSV](hr-javne-umjetnine_HR.csv) | [Excel](hr-javne-umjetnine_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-javne-umjetnine/) |
| [Catholic Churches in Croatia (Katoličke crkve u Hrvatskoj)](hr-katolicke-crkve.json) | 468 | 2208 KB | [CSV](hr-katolicke-crkve_HR.csv) | [Excel](hr-katolicke-crkve_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-katolicke-crkve/) |
| [Spomenici](hr-spomenici.json) | 240 | 26 KB | [CSV](hr-spomenici_HR.csv) | [Excel](hr-spomenici_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-spomenici/) |
| [Knjižnice](hr-knjiznice.json) | 188 | 23 KB | [CSV](hr-knjiznice_HR.csv) | [Excel](hr-knjiznice_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-knjiznice/) |
| [Kapelice uz put](hr-kapelice-uz-put.json) | 186 | 21 KB | [CSV](hr-kapelice-uz-put_HR.csv) | [Excel](hr-kapelice-uz-put_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-kapelice-uz-put/) |
| [Muzeji u Hrvatskoj (Museums in Croatia)](hr-muzeji.json) | 149 | 33 KB | [CSV](hr-muzeji_HR.csv) | [Excel](hr-muzeji_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-muzeji/) |
| [Samostani](hr-samostani.json) | 114 | 14 KB | [CSV](hr-samostani_HR.csv) | [Excel](hr-samostani_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-samostani/) |
| [Vjerski uredi](hr-vjerski-uredi.json) | 112 | 13 KB | [CSV](hr-vjerski-uredi_HR.csv) | [Excel](hr-vjerski-uredi_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-vjerski-uredi/) |
| [Raspela uz put](hr-raspela-uz-put.json) | 107 | 12 KB | [CSV](hr-raspela-uz-put_HR.csv) | [Excel](hr-raspela-uz-put_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-raspela-uz-put/) |
| [Galerije](hr-galerije.json) | 89 | 10 KB | [CSV](hr-galerije_HR.csv) | [Excel](hr-galerije_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-galerije/) |
| [Kazališta](hr-kazalista.json) | 86 | 10 KB | [CSV](hr-kazalista_HR.csv) | [Excel](hr-kazalista_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-kazalista/) |
| [Kina](hr-kina.json) | 79 | 9 KB | [CSV](hr-kina_HR.csv) | [Excel](hr-kina_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-kina/) |
| [Svjetska baština UNESCO-a u Hrvatskoj](hr-svjetska-bastina-unesco.json) | 10 | 12 KB | [CSV](hr-svjetska-bastina-unesco_HR.csv) | [Excel](hr-svjetska-bastina-unesco_HR.xlsx) | [View](https://listbase.org/hr/culture/hr-svjetska-bastina-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/culture/hr-spomen-obiljezja.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/culture/)
