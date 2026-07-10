# Factor Model Replication and GRS Testing

Course project for Georgia Tech finance and investments coursework.

## Overview

This project replicated Fama-French five-factor model tables and an AQR-style six-factor specification that replaces traditional HML with HML-DEV and adds momentum. The analysis then evaluated model fit using Gibbons, Ross, and Shanken tests across:

- 25 portfolios formed on size and book-to-market
- 10 industry portfolios

## Methods

- Fama-French five-factor replication
- HML-DEV and momentum extension
- Cross-sectional factor regression analysis
- GRS testing of joint alpha significance
- Interpretation of model complexity versus pricing performance

## Source Paper

This replication is based on Cliff Asness's AQR Capital Management article, *Our Model Goes to Six and Saves Value From Redundancy Along the Way*. The paper discusses the Fama-French five-factor model, the addition of momentum, and the use of a more timely HML-DEV value factor.

The source PDF is not redistributed in this public repository because it is copyrighted material.

## Artifact

- `factor-model-replication-grs.pdf`: final assignment report
- `hml-dev-factors-monthly.xlsx`: monthly factor workbook for the HML-DEV / momentum replication analysis

## Code

- [Google Colab notebook](https://colab.research.google.com/drive/14_b-g_USwEM8sBwEdaLHbNaGkBMglgNp?usp=sharing)

## Key Takeaway

Adding HML-DEV and momentum did not automatically improve joint pricing performance under the GRS lens; for the tested portfolios, alphas remained jointly significant.
