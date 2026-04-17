
README.md
Project: Analysis of import trends for HS 070960 (peppers, fresh or chilled)
Countries: Germany (DE), Poland (PL), United Kingdom (UK)
Date: 04/17/2026

Project goal
Analyze tendencies and trends of imports of goods under HS 070960 into Germany, Poland and the UK. Produce cleaned, merged datasets, statistical comparisons, visualizations, and a presentation summarizing findings.

Key objectives
Extract and consolidate international trade data for HS 070960 for DE, PL, and UK.
Clean and harmonize product naming (create “universal” pepper names).
Enrich dataset with scraped/exporter country information for typical peppers.
Produce statistical results and comparisons across countries and time.
Visualize trends and create slides for interim check and final presentation.
Tasks (from images / project board)
Extract trading data from World (UN Comtrade / other sources) for DE, PL, UK.
Cleaning data and mapping dataframes with "universal" pepper names.
AI scraping of typical peppers regarding export country (scrape exporter/product examples).
Make statistical results and comparisons (volumes, values, growth rates, shares).
Visualization of data (time series, share by origin, heatmaps, maps).
Combining scraped data with UN trading data (merge on product/producer/country).
Interim check and analysis (progress review).
Presentation (final slides summarizing methodology, results, recommendations).
Data sources
UN COMTRADE / UN trade databases (HS 070960 export/import flows)
National customs/trade statistics (optional: Germany, Poland, UK statistical offices)
Web sources for typical pepper exporters (marketplaces, reports) — scraped via AI / scrapers
Supplementary datasets: exchange rates, population, GDP (for normalization)
Data pipeline (recommended)
Data extraction
Query UN COMTRADE for HS 070960 for DE, PL, UK (both import and world export flows).
Preprocessing & cleaning
Convert numeric columns; standardize country and HS codes.
Map product names to a universal pepper naming scheme.
Handle missing values and outliers.
Enrichment
Scrape typical pepper product names and exporter countries; create lookup table.
Merge scraped info with trade data on exporter and product fields.
Analysis
Compute totals, year-over-year growth, CAGR, market shares, top exporters.
Compute differences and comparisons between DE/PL/UK.
Visualization & reporting
Create time series charts, stacked area charts, geographic maps, bar charts of top exporters.
Prepare slides for interim check and final presentation.
Delivery
Final cleaned datasets (CSV/Parquet), notebooks/scripts, visual assets, and slides.
Outputs / Deliverables
Cleaned, documented dataset for HS 070960 imports into DE, PL, UK.
Scripted extraction and cleaning pipeline (Python notebooks / .py).
Mapping table of universal pepper names.
Scraped exporter/product dataset.
Statistical summary (tables of top exporters, growth rates, category comparisons).
Visualizations (PNG/SVG) and slide deck (PDF/PPTX).
README and methods documentation.
Analysis ideas / metrics
Annual import value and quantity per country.
Growth rates (YoY, CAGR).
Market share of origin countries for each importer.
Price per unit (value / quantity) trends and differences.
