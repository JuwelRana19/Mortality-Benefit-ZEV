# ZEV Interventions, Mortality Benefit and Environmental Justice

This folder includes **reproducible R code** for the **Health Benefits and Equity Implications of Zero-Emission Transportation on Nonaccidental Mortality from Traffic-Related Air Pollution in Toronto, Canada: A Causal Analysis of Multipollutant Exposures** Manuscript Analysis and Visualization.

Authors: Juwel Rana, Jay S. Kaufman, Marianne Hatzopoulou, Jad Zalzal, Chen Chen, Alexander P. Keil, Tarik Benmarhnia,  Hong Cheng

Raw microdata, census extracts, and large derived datasets are **not** included.

## Related work

- Public analysis builds on standard R packages such as `sf`, `data.table`, and `tvcQGComp`.

## Repository layout

| Path | Purpose |
|------|---------|
| `scripts/` | Main analysis pipelines (add sanitized `.R` files here) |
| `data/README.md` | How to obtain restricted inputs locally |
| `CITATION.cff` | Software and manuscript citation metadata |

## Data availability and privacy

Census, exposure, and health-linked inputs are **not** included here. 

- CanCHEC Cohort data are accessible through Statistics Canada's Research Data Center program. Environmental exposure data are available upon request to the original authors.
- A toy dataset is included for replication purposes

See `.gitignore` for excluded file types.

## Requirements

- R (>= 4.2 recommended)
- Key packages: `sf`, `data.table`, `ggplot2`, `qgcomp`, and others as noted in scripts

## Acknowledgments
This study was funded by Health Canada under the Air Quality Program of the Government of Canada.

## Citation

**APA**

>Rana, J., Kaufman, J. S., Hatzopoulou, M., Zalzal, J., Chen, C., Keil, A. P., Benmarhnia, T., & Chen, H. (2026) *Health Benefits and Equity Implications of Zero-Emission Transportation on Nonaccidental Mortality from Traffic-Related Air Pollution in Toronto, Canada: A Causal Analysis of Multipollutant Exposures* [Under Review].

## Contact

Juwel Rana — juwelrana@saistbd.org
