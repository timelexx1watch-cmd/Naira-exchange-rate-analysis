# Naira-exchange-rate-analysis
# Naira Exchange Rate Driver Analysis (2019–2026)

    A quantitative investigation into what drives the value
    of the Nigerian Naira, using 7 years of monthly data
    across 6 macroeconomic variables.

    ## Research Question
    Is the naira primarily driven by CBN monetary policy
    or global dollar strength (DXY)?

    ## Key Findings
    - CBN MPR accounts for 52.9% of explained naira variation
    - Inflation accounts for 24.6%
    - DXY (dollar index) accounts for 9.0% — real but secondary
    - Pre-reform R² = 0.020 vs Post-reform R² = 0.358
    - June 2023 FX unification confirmed as structural break
      (Chow F = 49.77, p ≈ 0.000)
    - Only FX Reserves and Inflation Granger-cause naira
    - CBN is reactive not proactive — rate hikes follow
      naira weakness, they do not prevent it

    ## Data Sources
    | Variable     | Source                        |
    |---|---|
    | USD/NGN rate | Yahoo Finance                 |
    | DXY index    | Yahoo Finance                 |
    | Brent crude  | Yahoo Finance                 |
    | FX Reserves  | World Bank + CBN              |
    | Inflation    | World Bank + NBS              |
    | CBN MPR      | CBN MPC communiqués           |

    ## Tools & Libraries
    Python | pandas | numpy | statsmodels | scipy
    yfinance | wbdata | matplotlib | seaborn

    ## Notebook Structure
    - Section 1: Data Collection & Wrangling
    - Section 2: Exploratory Data Analysis
    - Section 3: Statistical Testing
    - Section 4: Regression Modelling & Attribution
    - Section 5: Summary & Conclusions
