# Turizam (Tourism)

13 datasets — 5,807 records

> Browse at [listbase.org/hr/tourism/](https://listbase.org/hr/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Turistički apartmani](hr-turisticki-apartmani.json) | 1,906 | 195 KB | [CSV](hr-turisticki-apartmani_HR.csv) | [Excel](hr-turisticki-apartmani_HR.xlsx) | [View](https://listbase.org/hr/tourism/hr-turisticki-apartmani/) |
| [Pansioni](hr-pansioni.json) | 1,529 | 156 KB | [CSV](hr-pansioni_HR.csv) | [Excel](hr-pansioni_HR.xlsx) | [View](https://listbase.org/hr/tourism/hr-pansioni/) |
| [Kampovi](hr-kampovi.json) | 506 | 52 KB | [CSV](hr-kampovi_HR.csv) | [Excel](hr-kampovi_HR.xlsx) | [View](https://listbase.org/hr/tourism/hr-kampovi/) |
| [Atrakcije](hr-atrakcije.json) | 349 | 37 KB | [CSV](hr-atrakcije_HR.csv) | [Excel](hr-atrakcije_HR.xlsx) | [View](https://listbase.org/hr/tourism/hr-atrakcije/) |
| [Turističke zajednice u Republici Hrvatskoj](hr-turisticke-zajednice.json) | 312 | 112 KB | [CSV](hr-turisticke-zajednice_HR.csv) | [Excel](hr-turisticke-zajednice_HR.xlsx) | [View](https://listbase.org/hr/tourism/hr-turisticke-zajednice/) |
| [Vidikovci](hr-vidikovci.json) | 288 | 30 KB | [CSV](hr-vidikovci_HR.csv) | [Excel](hr-vidikovci_HR.xlsx) | [View](https://listbase.org/hr/tourism/hr-vidikovci/) |
| [Kuće za odmor](hr-kuce-za-odmor.json) | 279 | 29 KB | [CSV](hr-kuce-za-odmor_HR.csv) | [Excel](hr-kuce-za-odmor_HR.xlsx) | [View](https://listbase.org/hr/tourism/hr-kuce-za-odmor/) |
| [Hosteli](hr-hosteli.json) | 252 | 27 KB | [CSV](hr-hosteli_HR.csv) | [Excel](hr-hosteli_HR.xlsx) | [View](https://listbase.org/hr/tourism/hr-hosteli/) |
| [Planinarski domovi](hr-planinarski-domovi.json) | 122 | 14 KB | [CSV](hr-planinarski-domovi_HR.csv) | [Excel](hr-planinarski-domovi_HR.xlsx) | [View](https://listbase.org/hr/tourism/hr-planinarski-domovi/) |
| [Turističko-informativni centri (TIC) u Hrvatskoj](hr-turisticko-informativni-centri.json) | 111 | 35 KB | [CSV](hr-turisticko-informativni-centri_HR.csv) | [Excel](hr-turisticko-informativni-centri_HR.xlsx) | [View](https://listbase.org/hr/tourism/hr-turisticko-informativni-centri/) |
| [Plažni resorti](hr-plazni-resorti.json) | 83 | 10 KB | [CSV](hr-plazni-resorti_HR.csv) | [Excel](hr-plazni-resorti_HR.xlsx) | [View](https://listbase.org/hr/tourism/hr-plazni-resorti/) |
| [Kamp odmorišta za kampere](hr-kamp-odmorista.json) | 60 | 7 KB | [CSV](hr-kamp-odmorista_HR.csv) | [Excel](hr-kamp-odmorista_HR.xlsx) | [View](https://listbase.org/hr/tourism/hr-kamp-odmorista/) |
| [Nacionalni parkovi i parkovi prirode Hrvatske](hr-parkovi.json) | 10 | 8 KB | [CSV](hr-parkovi_HR.csv) | [Excel](hr-parkovi_HR.xlsx) | [View](https://listbase.org/hr/tourism/hr-parkovi/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/tourism/hr-turisticki-apartmani.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/tourism/)
