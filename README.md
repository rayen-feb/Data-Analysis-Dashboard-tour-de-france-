# Data-Analysis-Dashboard-tour-de-france-
Data-Analysis-Dashboard( tour de france) 
# Tour de France Business Intelligence Project

## Overview
This project is a Business Intelligence (BI) analysis of the Tour de France, focusing on stage characteristics, riders, and team performance. The aim is to provide insights for decision-making, visualize key metrics, and explore patterns in stage outcomes, rider performance, and team strategies.

The project includes:

- Data collection, integration, and validation
- Data transformation and cleaning
- Data warehouse modeling (star schema)
- KPI definition and analysis
- Visualizations and dashboard creation for BI insights
  
![Alt text](/1.jpg)


## Project Structure

### 1. Data Sources
The project uses historical data from the Tour de France, including:

- **Stages**: stage number, type, distance, year, winner
- **Riders**: name, team, nationality
- **Teams**: team name, country
- **Results**: stage winner, average speed, time gaps

---

### 2. Data Integration & Transformation
- **Integration**: Consolidates data from multiple sources (CSV, online datasets, and historical records) into a unified format.
- **Transformation**: Includes cleaning, normalization, and aggregation to create a consistent dataset suitable for BI analysis.
- **Validation**: Ensures data quality by checking for missing values, duplicates, and consistency across related tables.

---

### 3. Data Warehouse Modeling
- **Star Schema** designed for analysis:
  - **Fact Table**: `StageResults`
    - Contains metrics such as distance, stage type, and winner
  - **Dimension Tables**:
    - `Riders`: Rider information
    - `Teams`: Team information
    - `Stages`: Stage characteristics
    - `Years`: Year of the stage
- Supports efficient analysis of KPIs and visualization.

---

### 4. Key Performance Indicators (KPIs)
- **Stages Analysis**:
  - Average distance by type of stage
  - Count of stages won by each rider
  - Average distance by year
- **Rider & Team Analysis**:
  - Number of stage wins per rider and team
  - Average speed per rider
  - Performance trends over years

---

### 5. Visualizations
- **Stage Analysis**:
  - Bar charts, line charts, and maps showing stage distances and winners
  - ![Alt text](images/6.jpg)
- **Rider & Team Analysis**:
  - Leaderboards for riders and teams
  - Trend analysis of performance over time
  - ![Alt text](images/5.jpg)
- **Dashboard**:
  - Interactive filters to select stage type, year, or team
  - KPIs displayed in cards for quick insights
![Alt text](images/1.jpg)
![Alt text](images/3.jpg)
---

### 6. BI Objectives
- Analyze factors affecting stage outcomes
- Identify trends in rider and team performance
- Segment stages and riders by characteristics
- Support decision-making for team strategies and fan engagement

---

### 7. Tools & Technologies
- **Data Handling**: R, Python, Excel
- **Visualization**: Power BI / Tableau
- **Database**: SQL for DW implementation
- **Dashboard**: Interactive filters, charts, and maps

---

### 8. How to Use
1. Clone the repository:
```bash
git clone https://github.com/rayen-feb/Data-Analysis-Dashboard-tour-de-france-/
