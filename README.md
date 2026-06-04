# 30ruling-research

VU research project
**Research Paper** — BSc Economics and Business Economics, Vrije Universiteit Amsterdam
**Course:** E_EBE2_RP — Research Paper, Period 2.6 (2025–2026)
**Supervisor:** Prof. Dr. Henri L.F. de Groot
**Author:** Alona Sycheska

## Overview

This paper investigates whether the 2019 reform of the Dutch 30% ruling — which reduced the maximum benefit duration from 8 to 5 years — had a measurable effect on highly skilled migration inflows to the Netherlands. Using a difference-in-differences framework, we compare skilled migration to the Netherlands with comparable EU countries that had stable tax treatment of skilled migrants during the same period.

## Research Question

What is the effect of the 2019 tightening of the 30% ruling on highly skilled migration inflows to the Netherlands?

## Data Sources

- **CBS StatLine** — Immigration by migration motive, nationality, and region ([opendata.cbs.nl](https://opendata.cbs.nl))
- **IND** — Knowledge migrant permit statistics ([ind.nl](https://ind.nl))
- **Eurostat** — First residence permits by reason and country ([ec.europa.eu/eurostat](https://ec.europa.eu/eurostat))
- **OECD** — International migration database and tax statistics

## Methods

- Difference-in-differences (DiD)
- Event study design
- Panel regression with country and year fixed effects

## Repository Structure

```
├── data/              # Raw and processed data (not tracked)
├── scripts/           # R scripts for analysis
├── output/            # Figures, tables, and results
├── paper/             # RMarkdown source and compiled paper
├── references/        # Literature and notes
├── .gitignore
└── README.md
```

## Reproducibility

All analysis is done in R. To replicate:

1. Clone this repository
2. Place raw data files in `data/` (see Data Sources above)
3. Run scripts in `scripts/` in numbered order

## Key References

- Kleven, H.J., Landais, C., Saez, E., & Schultz, E. (2014). Migration and wage effects of taxing top earners. *Quarterly Journal of Economics*, 129(1), 333–378.
- Timm, L., Giuliodori, M., & Muller, P. (2025). Tax Incentives for Migrants With Mid-Level Earnings. *American Economic Journal: Applied Economics*, 17(3), 42–79.
- Marie, O., Pereira dos Santos, J., & Singhal, M. (2023). Tax-Induced Emigration: Who Flees High Taxes? *Tinbergen Institute Discussion Paper* 2023-053/V.

## License

This project is for academic purposes. Please cite appropriately if you use any part of it.
