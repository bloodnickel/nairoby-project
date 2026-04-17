
**Analysis of HS 070960 Imports (peppers, fresh or chilled)**

Date: 04/17/2026

Project: Analyze import trends of HS 070960 (peppers, fresh or chilled) into Germany (DE), Poland (PL), and the United Kingdom (UK).

-----
**Project goal**

Analyze tendencies and trends of imports of HS 070960 into DE, PL, and UK. Produce cleaned, merged datasets, statistical comparisons, visualizations, and a presentation summarizing findings and recommendations.

-----
**Key objectives**

- Extract and consolidate international trade data for HS 070960 for DE, PL, and UK.
- Clean and harmonize product naming (create “universal” pepper names).
- Enrich dataset with scraped exporter-country examples for typical peppers.
- Produce statistical results and comparisons across countries and time.
- Visualize trends and create slides for interim check and final presentation.
-----
**Data sources**

- UN COMTRADE (HS 070960 export/import flows)
- National customs/trade statistics (optional: Germany, Poland, UK statistical offices)
- Web sources for typical pepper exporters (marketplaces, industry reports) — scraped
- Supplementary datasets: exchange rates, population, GDP (for normalization)
-----
**Data pipeline (recommended)**

1. Data extraction
   1. Query UN COMTRADE for HS 070960 for DE, PL, UK (imports) and world exports (origins).
1. Preprocessing & cleaning
   1. Standardize numeric columns, country names/codes, HS codes.
   1. Map product descriptions to a universal pepper naming scheme.
   1. Handle missing values, inconsistent units, and outliers.
1. Enrichment
   1. AI-assisted scraping of typical pepper varieties and exporter countries.
   1. Build a lookup table linking common product names → universal names → typical exporters.
1. Analysis
   1. Compute totals, YoY growth, CAGR, market shares, top exporters, price-per-unit.
   1. Compare DE / PL / UK across metrics and over time.
1. Visualization & reporting
   1. Time-series charts, stacked area charts, heatmaps, geographic maps, top-exporter bar charts.
   1. Prepare slides for interim check and final presentation.
1. Delivery
   1. Cleaned datasets, scripts/notebooks, visual assets, slide deck, README and methods docs.

