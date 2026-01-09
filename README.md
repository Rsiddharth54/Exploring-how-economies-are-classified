# Economic Classification Analysis: Beyond GNI Per Capita

This repository contains a comprehensive analysis of economic classification systems, challenging the traditional reliance on Gross National Income (GNI) per capita as the sole criterion for classifying national economies.

Certified by London School of Economics (LSE)

## Research Question

**By which criteria should we classify economies? Does division based on GNI per capita levels make sense?**

## Project Overview

Traditional economic classification systems rely heavily on GNI per capita, which masks important dimensions of development. This project develops a multidimensional development index built on 7 equally weighted thematic dimensions:

1. **Income & Output** - GDP, GDP per capita, GNI per capita, GNI per capita at PPP
2. **Infrastructure & Technology** - Industry value added, electric power consumption, mobile subscriptions, high-technology exports
3. **Trade & Investment** - FDI inflows, trade ratios, gross capital formation
4. **Human Capital** - Education enrollment rates, business registration procedures
5. **Environmental** - CO₂ emissions, forest area, water productivity, agricultural value added
6. **Institutional Factors** - Military expenditure, debt service, ODA, remittances
7. **Health** - HIV prevalence, under-5 mortality, immunization coverage, life expectancy

## Findings

 Analysis reveals that multidimensional measurement can unearth policy-relevant distinctions that GNI classification would obscure, such as:
- Middle-income countries with robust human capital but weak infrastructure
- Countries with similar GNI per capita but vastly different development profiles
- The importance of non-monetary dimensions in sustainable development


## How to View the Analysis

**Open View_Report/How-Should-We-Classify-Economies?**

## Technologies Used

- **Python** - Primary analysis language
- **Pandas & NumPy** - Data manipulation and analysis
- **Scikit-learn** - Machine learning and statistical modeling
- **Matplotlib & Seaborn** - Data visualization
- **World Bank API** - Data collection
- **Quarto** - Document generation

## Data Sources

The analysis uses World Bank Development Indicators (WDI) data, including:
- Economic indicators (GDP, GNI, trade data)
- Social indicators (education, health metrics)
- Environmental indicators (emissions, natural resources)
- Institutional indicators (governance, financial flows)

## Methodology

1. **Data Collection**: Automated collection from World Bank API
2. **Data Preprocessing**: Cleaning, standardization, and imputation
3. **Dimensional Analysis**: Development of 7 thematic dimensions
4. **Statistical Modeling**: Clustering and classification analysis
5. **Visualization**: Comprehensive charts and interactive plots
6. **Policy Implications**: Analysis of classification differences

## Getting Started

1. Clone this repository
2. Install Python dependencies: `pip install pandas numpy scikit-learn matplotlib seaborn`
3. Open the HTML file for the complete analysis
4. Or run the Jupyter notebook for interactive exploration

## Authors

Group 8 - DS202W Data Science Course, LSE

## License

This project is for educational and research purposes. 
