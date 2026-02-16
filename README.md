```{=html}
<p align="center">
```
`<img src="novascore_banner.png" alt="NOVAscore v0.2 Banner" width="100%">`{=html}
```{=html}
</p>
```
# NOVAscore v0.2

### Macro-Stress Credit Risk, Capital & Pricing Simulation Framework

------------------------------------------------------------------------

## 📌 Overview

NOVAscore v0.2 is a macro-scenario credit risk simulation engine
designed to connect:

Macroeconomic stress → Firm deterioration → PD/LGD/EAD → Losses →
Capital → Pricing → Profitability

It generates a synthetic corporate credit portfolio and evaluates how
risk, capital requirements, and pricing sustainability evolve across
macroeconomic scenarios.

------------------------------------------------------------------------

## 🎯 Business Objective

This project helps answer:

-   How much capital is required under stress?
-   Is current pricing economically sustainable?
-   Which segments and sectors drive capital inflation?
-   When does flat pricing destroy value?

------------------------------------------------------------------------

## 🧠 Modeling Architecture

### Portfolio Structure

-   Segments: SME, Mid, Large\
-   Sectors: Cyclical, Industrial, Tech, Defensive\
-   Dynamic exposures (EAD)\
-   Macro-stress sensitivity

### Credit Risk Engine

-   PD via logistic transformation\
-   LGD stress-dependent\
-   EAD with utilization effect\
-   Bernoulli default simulation

### Economic Capital

EC = EL + 2.33 × UL

### Risk-Based Pricing

Required Return = EL + CoC × EC\
Required Spread = Required Return / EAD

------------------------------------------------------------------------

## 📊 Key Outputs

-   Risk driver evolution (PD, LGD, EAD)
-   Expected Loss (EL)
-   Economic Capital (EC)
-   Capital intensity (EC/EAD)
-   Break-even spread
-   Economic profit under fixed pricing
-   Segment & sector stress attribution

------------------------------------------------------------------------

## 🚀 How to Run

1.  Install dependencies:

pip install numpy pandas matplotlib

2.  Open the notebook:

NOVAscoreV02.ipynb

3.  Run all cells.

------------------------------------------------------------------------

## ⚠️ Disclaimer

This project is a synthetic simulation tool for educational and
strategic purposes. It is not a Basel-compliant regulatory capital
model.

------------------------------------------------------------------------

## 📜 License

MIT License (see LICENSE file)
