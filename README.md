# HUD-Amazonia

**HUD-Amazonia** is a geospatial data analysis project aimed at exploring and visualizing key socio-environmental indicators across the Amazon region. This repository leverages advanced geospatial techniques to analyze data related to population, education, indigenous territories, and protected areas, providing insights into the complex dynamics of the Amazon basin.

> **Note:** This project is currently under active development. Features, data, and analyses are subject to change as the project evolves.

---

## Objectives

The primary goal of this project is to create a comprehensive geospatial framework to:

1. **Map and analyze population distribution** across Amazonian countries using high-resolution raster data.
2. **Visualize educational access** by integrating school locations and education metrics with hexagonal grids.
3. **Identify overlaps between indigenous territories and environmental boundaries**, highlighting areas of socio-environmental importance.
4. **Support decision-making** by generating reproducible, data-driven visualizations and metrics.

---

## Key Features

- **Hexagonal Grid Analysis**: The project uses hexagonal grids at varying resolutions to aggregate and analyze spatial data efficiently.
- **Population Data Integration**: High-resolution population data from WorldPop is processed and visualized for age and gender-specific insights.
- **Education Metrics**: School data is integrated to assess educational access and infrastructure across the Amazon basin.
- **Indigenous Territories Mapping**: Indigenous territories are analyzed in relation to environmental and administrative boundaries.
- **Geospatial Visualization**: Interactive and static maps are generated to communicate findings effectively.

---

## Data Sources

The project integrates multiple datasets, including:

- **WorldPop**: High-resolution population data for age and gender groups.
- **Cartographic Boundary Files**: Administrative boundaries for Amazonian countries.
- **Indigenous Territories**: Spatial data on indigenous lands.
- **Protected Areas**: Shapefiles of protected regions.
- **Education Data**: School locations and metrics from national and regional sources.

---

## Tools and Libraries

The project is built using a robust geospatial data science stack, including:

- **Python Libraries**: `geopandas`, `urbanpy`, `matplotlib`, `contextily`, `rioxarray`, `osmnx`, `shapely`, and more.
- **Data Processing**: `pandas`, `tqdm`, `pandarallel` for efficient data manipulation.
- **Visualization**: `matplotlib`, `seaborn`, and `contextily` for creating maps and plots.

---

## Repository Structure

```sh
HUD-amazonia/
├── inputs/ # Raw input data (e.g., shapefiles, raster files)
├── outputs/    # Processed data and generated outputs
├── 1.AmazonasLimits.ipynb  # Notebook for Amazonian boundaries
├── 2.ContryPopulation.ipynb    # Notebook for population analysis
├── 3.AmazonasSchools.ipynb # Notebook for school data integration
├── 4.AmazonasSchoolsPlotsMaps.ipynb    # Notebook for schools viz
├── README.md # Project documentation (this file)
```

---

## Current Progress

- **Amazonas Limits**: Defined and cleaned the boundaries of the Amazon region.
- **Population Analysis**: Integrated WorldPop data for multiple countries and age groups.
- **School Data**: Processed and visualized school locations and education metrics.
- **Indigenous Territories**: Mapped and analyzed overlaps with Amazonian boundaries.

---

## Next Steps

1. Enhance data integration for protected areas and environmental metrics.
2. Develop interactive dashboards for stakeholders.
3. Refine visualizations for storytelling and decision-making.
4. Expand analysis to include additional socio-environmental indicators.

---

## How to Contribute

This project is open to collaboration! If you have expertise in geospatial analysis, data visualization, or storytelling, feel free to contribute by:

1. Forking the repository.
2. Submitting pull requests with improvements or new features.
3. Reporting issues or suggesting enhancements.

---

## Acknowledgments

This project is made possible by the contributions of open data providers, including WorldPop, national governments, and geospatial communities.

---

## Disclaimer

This repository is a work in progress. Data and analyses are preliminary and may contain inaccuracies. Use the outputs responsibly and verify results independently before making decisions.

---
