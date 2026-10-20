# Geografija (Geography)

17 datasets — 3,498 records

> Browse at [listbase.org/hr/geography/](https://listbase.org/hr/geography/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Gradovi i naseljena mjesta Hrvatske](hr-gradovi.json) | 1,135 | 240 KB | [CSV](hr-gradovi_HR.csv) | [Excel](hr-gradovi_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-gradovi/) |
| [Zeljeznicke postaje u Hrvatskoj](hr-zeljeznicke-postaje.json) | 731 | 277 KB | [CSV](hr-zeljeznicke-postaje_HR.csv) | [Excel](hr-zeljeznicke-postaje_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-zeljeznicke-postaje/) |
| [Gradovi i općine Hrvatske (OSM)](hr-gradovi-opcine.json) | 532 | 187 KB | [CSV](hr-gradovi-opcine_HR.csv) | [Excel](hr-gradovi-opcine_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-gradovi-opcine/) |
| [Popis svih država svijeta](hr-drzave.json) | 250 | 116 KB | [CSV](hr-drzave_HR.csv) | [Excel](hr-drzave_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-drzave/) |
| [Emoji zastave država svijeta](hr-drzave-emoji-zastave.json) | 250 | 44 KB | [CSV](hr-drzave-emoji-zastave_HR.csv) | [Excel](hr-drzave-emoji-zastave_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-drzave-emoji-zastave/) |
| [Međunarodni telefonski pozivni brojevi država](hr-telefonski-pozivni-brojevi.json) | 248 | 52 KB | [CSV](hr-telefonski-pozivni-brojevi_HR.csv) | [Excel](hr-telefonski-pozivni-brojevi_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-telefonski-pozivni-brojevi/) |
| [Države – Afrika](hr-afrika-drzave.json) | 59 | 29 KB | [CSV](hr-afrika-drzave_HR.csv) | [Excel](hr-afrika-drzave_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-afrika-drzave/) |
| [Države – Europa](hr-europa-drzave.json) | 53 | 26 KB | [CSV](hr-europa-drzave_HR.csv) | [Excel](hr-europa-drzave_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-europa-drzave/) |
| [Države – Azija](hr-azija-drzave.json) | 50 | 25 KB | [CSV](hr-azija-drzave_HR.csv) | [Excel](hr-azija-drzave_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-azija-drzave/) |
| [Države – Sjeverna Amerika](hr-sjeverna-amerika-drzave.json) | 42 | 22 KB | [CSV](hr-sjeverna-amerika-drzave_HR.csv) | [Excel](hr-sjeverna-amerika-drzave_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-sjeverna-amerika-drzave/) |
| [Trajektne i brodske linije Jadrolinije](hr-trajektne-linije.json) | 38 | 21 KB | [CSV](hr-trajektne-linije_HR.csv) | [Excel](hr-trajektne-linije_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-trajektne-linije/) |
| [Najčešća prezimena u Hrvatskoj (Popular Croatian Surnames)](hr-prezimena.json) | 30 | 6 KB | [CSV](hr-prezimena_HR.csv) | [Excel](hr-prezimena_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-prezimena/) |
| [Države – Oceanija](hr-oceanija-drzave.json) | 27 | 15 KB | [CSV](hr-oceanija-drzave_HR.csv) | [Excel](hr-oceanija-drzave_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-oceanija-drzave/) |
| [Najpopularnija osobna imena u Hrvatskoj (Popular Croatian Forenames)](hr-osobna-imena.json) | 21 | 5 KB | [CSV](hr-osobna-imena_HR.csv) | [Excel](hr-osobna-imena_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-osobna-imena/) |
| [Države – Južna Amerika](hr-juzna-amerika-drzave.json) | 14 | 9 KB | [CSV](hr-juzna-amerika-drzave_HR.csv) | [Excel](hr-juzna-amerika-drzave_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-juzna-amerika-drzave/) |
| [Slapovi u Hrvatskoj](hr-slapovi.json) | 13 | 12 KB | [CSV](hr-slapovi_HR.csv) | [Excel](hr-slapovi_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-slapovi/) |
| [Države – Antarktika](hr-antarktika-drzave.json) | 5 | 5 KB | [CSV](hr-antarktika-drzave_HR.csv) | [Excel](hr-antarktika-drzave_HR.xlsx) | [View](https://listbase.org/hr/geography/hr-antarktika-drzave/) |

## Quick Start

```bash
# List all geography datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="geography") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/geography/hr-gradovi.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/geography/)
