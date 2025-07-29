# ASEAN Food Circularity System

A data-driven platform to address food waste for well-being and sustainability. **This project is a submission for the ASEAN Data Science Explorers 2025 and is not intended for full reproducibility.**

## Introduction

This project analyzes food waste and its relationship with food security in the ASEAN region. It uses data from the Food and Agriculture Organization (FAO) and other sources to identify key trends and provide insights for policymakers. The analysis is conducted using Python with libraries such as Pandas, Seaborn, and Matplotlib.

## Features

*   **Data Processing:** A comprehensive data processing pipeline that cleans and transforms raw data from multiple sources.
*   **In-depth Analysis:** Detailed analysis of food loss, food security, and their socio-economic and environmental impacts.
*   **Actionable Insights:** The project provides data-driven insights to support the development of effective food waste reduction strategies.

## Architecture and Workflow

The project follows a structured data analysis workflow:

1.  **Data Ingestion:** Raw data is sourced from FAOSTAT and other relevant datasets.
2.  **Data Processing:** The data is cleaned, processed, and transformed using Jupyter Notebooks.
3.  **Data Analysis:** The processed data is analyzed to identify trends, patterns, and correlations.
4.  **Output:** The results are presented in the form of tables, charts, and key findings.

## Project Structure

```
.
├── .gitignore
├── LICENSE
├── pdm.lock
├── pyproject.toml
├── readme-instruction.md
├── README.md
├── data
│   ├── FAOSTAT
│   ├── final
│   └── processed
├── notebooks
│   ├── 01-faostat-processing.ipynb
│   ├── 02-data-processing.ipynb
│   └── 03-data-analysis.ipynb
└── project_reference
```

*   **data:** Contains the raw, processed, and final datasets.
*   **notebooks:** Contains the Jupyter Notebooks for data processing and analysis.
*   **project\_reference:** Contains project reference files.


## Note on Data and Models

**Important:** The raw data used in this project is not included in the repository due to its large size. Some scripts or notebooks may reference files that are not available due to these data restrictions. This project is not intended for reproducibility; it is provided solely as a demonstration and submission for the ASEAN Data Science Explorers 2025 competition.

## Results and Outputs

The key findings of this analysis are detailed in the `03-data-analysis.ipynb` notebook. The results highlight a critical issue termed the "Food Loss Paradox" within the ASEAN region, where countries with significant food loss also face challenges with undernourishment.

### The Food Loss Paradox

The analysis reveals a paradoxical situation where substantial amounts of food are lost per capita, while a notable percentage of the population remains undernourished. This suggests inefficiencies in the food supply chain that, if addressed, could simultaneously reduce waste and improve food security.

### GHG Emissions Prevention

The project also emphasizes the potential for reducing greenhouse gas emissions through improved food waste management practices. With proper management, the food waste that is currently lost could be processed properly to generate energy or compost, thus preventing unnecessary emissions associated with food waste decomposition in landfills.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.