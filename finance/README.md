# Financije i trgovina (Finance & Trade)

8 datasets — 729 records

> Browse at [listbase.org/hr/finance/](https://listbase.org/hr/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Medijalne cijene nekretnina po m² po jedinicama lokalne samouprave (2012–2019)](hr-cijene-nekretnina-jls.json) | 556 | 151 KB | [CSV](hr-cijene-nekretnina-jls_HR.csv) | [Excel](hr-cijene-nekretnina-jls_HR.xlsx) | [View](https://listbase.org/hr/finance/hr-cijene-nekretnina-jls/) |
| [Mjenjačnice](hr-mjenjacnice.json) | 116 | 13 KB | [CSV](hr-mjenjacnice_HR.csv) | [Excel](hr-mjenjacnice_HR.xlsx) | [View](https://listbase.org/hr/finance/hr-mjenjacnice/) |
| [Banke u Zagreb — SWIFT/BIC kodovi (Zagreb bank SWIFT/BIC codes)](hr-zagreb-banke.json) | 37 | 7 KB | [CSV](hr-zagreb-banke_HR.csv) | [Excel](hr-zagreb-banke_HR.xlsx) | [View](https://listbase.org/hr/finance/hr-zagreb-banke/) |
| [Banke u Rijeka — SWIFT/BIC kodovi (Rijeka bank SWIFT/BIC codes)](hr-rijeka-banke.json) | 5 | 3 KB | [CSV](hr-rijeka-banke_HR.csv) | [Excel](hr-rijeka-banke_HR.xlsx) | [View](https://listbase.org/hr/finance/hr-rijeka-banke/) |
| [Banke u Split — SWIFT/BIC kodovi (Split bank SWIFT/BIC codes)](hr-split-banke.json) | 5 | 3 KB | [CSV](hr-split-banke_HR.csv) | [Excel](hr-split-banke_HR.xlsx) | [View](https://listbase.org/hr/finance/hr-split-banke/) |
| [Banke u Varaždin — SWIFT/BIC kodovi (Varaždin bank SWIFT/BIC codes)](hr-varazdin-banke.json) | 4 | 2 KB | [CSV](hr-varazdin-banke_HR.csv) | [Excel](hr-varazdin-banke_HR.xlsx) | [View](https://listbase.org/hr/finance/hr-varazdin-banke/) |
| [Banke u Šibenik — SWIFT/BIC kodovi (Šibenik bank SWIFT/BIC codes)](hr-sibenik-banke.json) | 3 | 2 KB | [CSV](hr-sibenik-banke_HR.csv) | [Excel](hr-sibenik-banke_HR.xlsx) | [View](https://listbase.org/hr/finance/hr-sibenik-banke/) |
| [Banke u Zadar — SWIFT/BIC kodovi (Zadar bank SWIFT/BIC codes)](hr-zadar-banke.json) | 3 | 2 KB | [CSV](hr-zadar-banke_HR.csv) | [Excel](hr-zadar-banke_HR.xlsx) | [View](https://listbase.org/hr/finance/hr-zadar-banke/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.hr.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.hr.listbase.org/finance/hr-cijene-nekretnina-jls.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hr/finance/)
