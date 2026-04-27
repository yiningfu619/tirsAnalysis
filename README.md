# Spatial–Temporal Dynamics of Aedes-Borne Viruses and Targeted Indoor Residual Spraying (TIRS) Effectiveness in Mérida, 2023

------------------------------------------------------------------------

# Project Overview

This project analyzes trial-level epidemiological data to identify patterns of local disease transmission. The core focus is on understanding how infections spread within defined geographic clusters and over time. Using cluster-based analyses, we categorize transmission events as “local” when they occur within the same trial-defined geographic cluster, enabling more precise mapping of outbreak dynamics.

Key objectives include:

- Identifying optimal clustering structures in trial regions.
- Quantifying local vs. non-local transmission events.
- Supporting data-driven decisions for targeted interventions.

The workflow integrates data cleaning, transformation, and visualization, providing a reproducible framework for exploring spatial and temporal patterns in clinical trial data. All analyses are conducted in R, with clear documentation to facilitate transparency and scalability for future studies.

# Real-World Impact

This interactive dashboard provides a framework for analyzing the spatiotemporal clustering of Aedes-borne viruses using test-negative design data, allowing users to determine whether disease transmission is localized or fully disseminated. By revealing that targeted indoor residual spraying (TIRS) is most effective during the early, highly clustered phases of an outbreak, these findings guide public health officials to deploy rapid interventions before community transmission becomes widespread.

# Repository Contents

- index.Rmd: An interactive analytical dashboard built with flexdashboard. This application provides a dynamic user interface to visually explore participant demographics, temporal case distributions, and real-time calculations of the tau statistic by allowing users to seamlessly adjust temporal windows and seasonal phases.

# Software Requirements and Dependencies

To run the dashboard (`index.Rmd`) in this repository, you will need R and the following packages installed:

- flexdashboard (Interactive dashboard authoring)

- shiny (Interactive web applications framework)

- shinydashboard (Dashboard themes and layouts for Shiny)

- dplyr (Data manipulation)

- ggplot2 (Data visualization)

- lubridate (Date and time manipulation)

- tidyr (Data tidying)

- scales (Formatting plot axes and legends)

- plotly (Interactive plots and visualizations)

- DT (Interactive HTML data tables)

You can install the required packages using the following command in your R console:

```bash
install.packages(c("flexdashboard", "shiny", "shinydashboard", "dplyr", "ggplot2", "lubridate", "tidyr", "scales", "plotly", "DT"))
```

# Usage

Open index.Rmd in RStudio and click "Run Document" to launch the interactive Shiny dashboard for dynamic data exploration.