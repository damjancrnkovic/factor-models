# Machine learning based factor estimation in factor models of asset returns

Implementation and supporting material for the bachelor thesis **"Procjena faktora u faktorskim modelima povrata imovina zasnovana na strojnom učenju"** / **"Machine Learning Based Factor Estimation in Factor Models of Asset Returns"**.

The project investigates whether an LSTM neural network can improve the estimation of risk premiums in the Fama-French three-factor model compared with classical approaches such as the historical mean and Fama-MacBeth regression. The evaluation is performed out-of-sample using 49 industry portfolios and monthly financial data. :contentReference[oaicite:0]{index=0}

## Overview

The project compares four approaches:

- Historical mean
- Fama-MacBeth regression
- Oracle estimate (idealized upper bound)
- LSTM neural network

The LSTM uses historical factor returns together with an additional macroeconomic variable to estimate time-varying factor premiums. :contentReference[oaicite:1]{index=1}

The results indicate that the LSTM outperforms the feasible classical methods, although predicting factor premiums remains a difficult problem. :contentReference[oaicite:2]{index=2}

## Data

The analysis uses:

- Fama-French factors: **MKT, SMB, HML**
- 49 U.S. industry portfolios
- Risk-free rate
- Shiller's **Excess CAPE Yield (ECY)**

The sample covers monthly observations from January 1970 to February 2026. :contentReference[oaicite:3]{index=3}

## Disclaimer

This repository is **not an official document** of the Faculty of Electrical Engineering and Computing (FER), the University of Zagreb, or any other institution.

The original thesis was written **initially in Croatian**. The English version and related English-language material in this repository were translated with the assistance of **LLM agents** and may therefore contain translation or interpretation errors. The original Croatian thesis should be considered the authoritative version.

