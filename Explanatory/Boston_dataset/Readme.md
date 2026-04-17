# Boston Housing Market Analysis

## Project Overview
This notebook provides a comprehensive exploratory data analysis (EDA) of the Boston House Price dataset. The goal is to identify and visualize the primary socio-economic and environmental factors that influence residential property values in Boston.

## Dataset Specifications
The dataset consists of 506 observations with 14 variables, including environmental metrics (NOX), urban infrastructure accessibility (RAD, DIS), and neighborhood demographics (LSTAT, CRIM).

### Core Features:
*   **MEDV**: Median value of owner-occupied homes (Target Variable).
*   **RM**: Average number of rooms per dwelling.
*   **LSTAT**: Percentage of lower status population.
*   **PTRATIO**: Pupil-teacher ratio by town.
*   **DIS**: Weighted distances to five Boston employment centers.
*   **NOX**: Nitric oxides concentration (parts per 10 million).

## Key Findings
Based on our analysis, the following trends were observed:
1.  **Housing Capacity**: A strong positive correlation exists between the number of rooms (RM) and property value.
2.  **Socio-Economic Impact**: Areas with a higher percentage of lower-income status (LSTAT) show a significant decline in median home values.
3.  **Urban Proximity**: There is a clear negative correlation between distance to employment centers (DIS) and industrial density (INDUS) as well as pollution (NOX), suggesting that urban cores remain the primary hubs for industry and environmental impact.
