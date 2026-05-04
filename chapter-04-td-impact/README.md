# Chapter 4 — Transmission & Distribution Vulnerability to Climate Change

**Status**: Public. Code maintained in a dedicated satellite repository (mirrors the Chapter 1 pattern).

> *Note on numbering*: this folder is labelled "Chapter 4" because it is the **fourth substantive contribution** of the thesis. In the integrated thesis manuscript it appears as **Chapter 6**, "Assess climate change and variability impacts on transmission and distribution system components".

## Code

https://github.com/ODOU/ampacity-westafrica-climate

The satellite repo contains the full reproducible analysis pipeline (Python + notebooks + SLURM submission templates) plus 28 publication-grade figures and three summary CSVs, under MIT licence.

## Summary

First spatially explicit assessment of climate-change impacts on overhead-transmission-line ampacity in West Africa. Applies a steady-state Bartos-et-al. (2016) thermal balance to a representative ACSR (BISON 382-AL1/49-ST1A) conductor, forced by ERA5 reanalysis (1985–2014) and NEX-GDDP-CMIP6 multi-model-mean projections (2015–2070) under SSP2-4.5 and SSP5-8.5.

## Headline findings

| Region | Historical mean | Mid-century change (SSP5-8.5) | Notable seasonal signal |
|---|---|---|---|
| **Guinea** | 962 A | +20.7 % | Uniform gains driven by monsoon-wind intensification |
| **Sahelian** | 1,147 A | +1.2 % (annual) | **Winter decline of −4.9 %** — Harmattan weakening |
| **Soudanian** | 1,041 A | +7.7 % | Intermediate pattern, slight winter decline |

Wind-speed evolution — not temperature — is the leading driver of projected ampacity change across West Africa, in direct contrast to the temperature-dominated regime documented in mid-latitude studies (Bartos et al. 2016).

## Coupling with Chapter 3 (ReEDS capacity expansion)

The Sahel-band winter de-rating identified here compounds with rising demand (Chapter 2) and expanded generation needs (Chapter 3) along the planned WAPP corridors that traverse the Sahelian zone, motivating the climate-informed transmission planning recommendation in the thesis synthesis.

## Citation

> Odou, T. (2026). *Climate change impacts on transmission line ampacity in West Africa — analysis code* (Version 1.0.0) [Computer software]. MIT License. https://github.com/ODOU/ampacity-westafrica-climate
