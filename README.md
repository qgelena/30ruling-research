# 30ruling-research

## VU research project
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

- Bijlsma, M., Stäbler, D., Verheuvel, N., Ourak, W., Ferwerda, J., & Weel, B. ter. (2024). Kunde, kosten en keuzes: Evaluatie 30%-regeling, ETK-regeling & partiële buitenlandse belastingplicht 2016–2022. SEO Economisch Onderzoek, Amsterdam. SEO-rapport nr. 2024-78. https://www.seo.nl/wp-content/uploads/2024/06/2024-78-Kunde-kosten-en-keuzes.pdf
- Godar, S., Flamant, E., & Richard, G. (2021). New forms of tax competition in the European Union: An empirical investigation. EU Tax Observatory Report No. 3. https://www.taxobservatory.eu/www-site/uploads/2021/11/EU-Tax-Observatory-Report-3-Tax-Competition-November-2021-3.pdf
- Kleven, H.J., Landais, C., Saez, E., & Schultz, E. (2014). Migration and wage effects of taxing top earners: Evidence from the foreigners' tax scheme in Denmark. *Quarterly Journal of Economics*, 129(1), 333–378.
- Kleven, H.J., Landais, C., Muñoz, M., & Stantcheva, S. (2020). Taxation and migration: Evidence and policy implications. *Journal of Economic Perspectives*, 34(2), 119–142.
- Vankan, A., Brennenraedts, R., den Hertog, P., Driesse, M., & Veldman, J. (2017). Evaluatie 30%-regeling. Dialogic Innovation & Interaction, Utrecht. Commissioned by the Ministry of Finance. https://open.overheid.nl/documenten/ronl-844cbaf9b3266ed4801810c4a2991605d4ac5bb1/pdf
- Giarola, J.V.C., Marie, O., Cörvers, F., & Schmeets, H. (2023). Tax-Induced Emigration: Who Flees High Taxes? Evidence from the Netherlands. *Tinbergen Institute Discussion Paper* TI 2023-053/V.
- Moretti, E., & Wilson, D.J. (2017). The effect of state taxes on the geographical location of top earners. *American Economic Review*, 107(7), 1858–1903.
- Timm, L.M. (2025). *Migrants and Multinationals: Essays on the Local Effects of Globalization.* PhD Thesis, Universiteit van Amsterdam. Tinbergen Institute Research Series No. 880.
- Timm, L., Giuliodori, M., & Muller, P. (2025). Tax Incentives for Migrants With Mid-Level Earnings: Evidence from the Netherlands. *American Economic Journal: Applied Economics*, 17(3), 42–79.
- Akcigit, U., Baslandze, S., & Stantcheva, S. (2016). Taxation and the international mobility of inventors. *American Economic Review*, 106(10), 2930–2981.
- OECD (2025). *Taxing Wages 2025.* Paris: OECD Publishing.
- Belastingdienst (2024). *Besluit Woo-verzoek over de 30%-regeling.* 20 September 2024.
- Van der Werf, F., Nicolaas, H., Muermans, H., & Liu, J. (2023). *Kenniswerkers en zoekjaarders in Nederland: Een cohortstudie naar verblijf van kenniswerkers en zoekjaarders in Nederland.* IND/CBS, The Hague.
-Netherlands Chamber of Commerce, KVK. (2025). The expat scheme (30% ruling) for foreign employees in the Netherlands. Business.gov.nl. Retrieved June 11, 2026, from https://business.gov.nl/staff/employing-staff/the-expat-scheme-30-percent-ruling-in-the-netherlands/

## License

This project is for academic purposes. Please cite appropriately if you use any part of it.
