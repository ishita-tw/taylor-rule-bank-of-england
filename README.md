# Taylor Rule vs Bank of England Policy

## Overview

This project investigates how closely UK monetary policy has followed a simplified Taylor Rule benchmark since 2000.

The analysis uses Python and official UK macroeconomic data to construct a Taylor Rule benchmark and compare it with the Bank of England's actual Bank Rate.

## Research Question

**How closely has UK monetary policy followed a simplified Taylor Rule benchmark since 2000?**

The project also examines periods where actual Bank Rate diverged substantially from the benchmark and considers possible economic explanations for these differences.

## Methodology

The analysis uses monthly UK data on:

- **Bank Rate** - Bank of England
- **CPI inflation** - Office for National Statistics
- **Unemployment** - Office for National Statistics

A simplified Taylor Rule is constructed using an unemployment gap instead of the traditional output gap.

The project then:

1. Cleans and combines the datasets using Python
2. Calculates the Taylor Rule benchmark
3. Compares the benchmark with actual Bank Rate
4. Examines the largest policy gaps
5. Investigates the 2000 period and the 2022 inflation shock
6. Conducts a sensitivity analysis of the model assumptions

## Key Tools

- Python
- pandas
- Matplotlib
- Google Colab

## Data Sources

Data are sourced from the **Bank of England** and **Office for National Statistics (ONS)**.

The full analysis, code, visualisations, assumptions, results and references are contained in the notebook:

**[View the full analysis →](./UK_Taylor_Rule_Analysis.ipynb)**

## Limitations

The Taylor Rule is used as a simplified benchmark rather than a description of the Bank of England's actual policy-setting process.

Key limitations include the use of unemployment instead of the traditional output gap, assumptions about the neutral real interest rate and natural unemployment rate, constant model assumptions over time, and the change in the UK's inflation target during the sample period.

## References

Full references and source links are provided in the project notebook.
