# 🐟 Australian Seafood Industry Production Trade Analysis

An interactive Tableau dashboard exploring Australia's seafood industry through production trends, aquaculture and wild-catch comparisons, seafood commodity values, and long-term industry changes.

## Project Overview

This project investigates the Australian seafood industry using real industry datasets. The visualisation focuses on how seafood production and industry value have changed over time, how aquaculture compares with commercial wild-catch fishing, and which seafood commodities contribute most to the industry.

The dashboard was developed as part of **FIT3179 Data Visualisation at Monash University**.

The goal was to turn multiple datasets into a clear, interactive dashboard that allows users to explore the Australian seafood industry and identify important patterns without having to analyse the raw data themselves.

## Research Questions

The visualisation was designed to answer the following questions:

* How has Australian seafood production changed over time?
* How do aquaculture and wild-catch fishing compare?
* Which seafood commodities contribute the most value to the industry?
* How does seafood industry value differ across Australian jurisdictions?
* Which commodities have experienced the strongest growth or decline?
* How have commodity rankings changed over time?
* What long-term trends can be observed in the Australian seafood industry?

## Dataset Overview

The project uses four datasets containing information about seafood production, commodity values, Australian jurisdictions, and industry sectors.

### 1. Commodity Value by Year

**File:** `commodity_value_by_year_heatmap.xlsx`

This dataset contains the value of different Australian seafood commodities across multiple financial years.

**Main fields:**

* `Commodity`
* `Financial Year`
* `Value`

**Used for:**

* Top seafood commodities
* Commodity treemap
* Commodity value heatmap
* Commodity growth analysis
* Commodity ranking changes

### 2. Value by Jurisdiction and Sector

**File:** `value_by_jurisdiction_sector.xlsx`

This dataset contains seafood industry value across Australian jurisdictions and sectors.

**Main fields:**

* `Jurisdiction`
* `Category`
* `Year`
* `Value`
* `Financial Year`
* `Sector`

**Used for:**

* Aquaculture vs wild-catch comparison
* Seafood value by Australian jurisdiction
* Seafood value by state
* Long-term jurisdiction comparisons

### 3. Fisheries Production by Country

**File:** `fisheries_production_by_country.xlsx`

This dataset contains seafood production by country and year. The project uses the Australian records to investigate national seafood production trends.

**Main fields:**

* `Country`
* `Year`
* `Production (metric tons)`

**Used for:**

* Australian seafood production trend
* Historical production analysis

### 4. GVP FRDC Dataset

**File:** `GVP_FRDC_6-5-2021.xlsx`

This dataset contains additional Australian fisheries and aquaculture information, including industry value, jurisdictions, sectors, and seafood categories.

**Used for:**

* Supporting Australian industry analysis
* Comparing seafood sectors and jurisdictions
* Cross-checking relevant industry values

## Data Preparation

Before creating the visualisations, the datasets were cleaned and prepared for Tableau.

The preparation included:

* Removing unnecessary fields
* Renaming unclear column names
* Handling missing or inconsistent values
* Checking data types
* Selecting relevant financial years
* Simplifying the datasets for easier visual analysis
* Creating calculated fields for growth rates, rankings, and percentages

The cleaned data was then connected to Tableau to build the dashboard.

## Dashboard Visualisations

The dashboard contains 10 visualisations, combining standard charts with advanced visualisation idioms.

| #  | Visualisation        | Purpose                                                              |
| -- | -------------------- | -------------------------------------------------------------------- |
| 1  | Line Chart           | Shows Australian seafood production trends over time                 |
| 2  | Stacked Bar Chart    | Compares aquaculture and wild-catch fishing                          |
| 3  | Horizontal Bar Chart | Shows the top seafood commodities by value                           |
| 4  | Horizontal Bar Chart | Compares seafood industry value across Australian jurisdictions      |
| 5  | Vertical Bar Chart   | Compares seafood industry value across Australian states             |
| 6  | Treemap              | Shows the relative contribution of seafood commodities               |
| 7  | Scatter Plot         | Compares commodity value and growth                                  |
| 8  | Heatmap              | Shows commodity value patterns across financial years                |
| 9  | Bump Chart           | Shows changes in commodity rankings over time                        |
| 10 | Pie Chart            | Provides an overview of the global market share b/w countries        |
| 11 | Line Chart           | Shows the predicted value of the australian seafood industry by 2028 |

## Advanced Visualisation Idioms

The project includes several visualisation techniques beyond basic bar and line charts.

### Treemap

Used to show the relative contribution of different seafood commodities to the industry's total value.

### Scatter Plot

Used to compare commodity value with growth and identify commodities that perform strongly in both areas.

### Heatmap

Used to identify patterns and changes in commodity values across financial years.

### Bump Chart

Used to show how the ranking of seafood commodities changes over time.

## Dashboard Design

The dashboard was designed to provide a clear visual hierarchy.

* KPI cards are placed at the top to provide an immediate overview.
* Production and sector comparisons appear near the beginning.
* Commodity and jurisdiction comparisons follow.
* Advanced visualisations are placed in the later sections for deeper analysis.
* Consistent colours are used to distinguish sectors and categories.
* Numerical values are represented using colour intensity where appropriate.
* Unnecessary borders and gridlines were reduced to keep the dashboard clean.
* Tableau containers were used to maintain alignment and spacing.

## Interactivity

The dashboard includes interactive filters that allow users to explore the data from different perspectives.

Users can filter by:

* Financial year
* Seafood commodity
* Sector
* Australian jurisdiction, where applicable

These filters help users compare different periods and identify changes in the Australian seafood industry.

## Tools and Skills

**Tools:**

* Tableau
* Microsoft Excel
* GitHub

**Skills demonstrated:**

* Data cleaning and preparation
* Data integration
* Exploratory data analysis
* Data visualisation
* Tableau calculated fields
* Table calculations
* Dashboard design
* Interactive filtering
* Visual storytelling
* Data interpretation

## Project Structure

```text
australian-seafood-industry-visualisation/
│
├── README.md
├── dashboard/
├── data/
├── screenshots/
└── documentation/
```

## Data Sources

The datasets are based on Australian fisheries and aquaculture statistics and related seafood production data.

Official sources include:

* Australian Government Department of Agriculture, Fisheries and Forestry
* ABARES fisheries and aquaculture statistics
* Fisheries Research and Development Corporation (FRDC)
* Australian fisheries and seafood production datasets

Source links and dataset details are documented in the project files.

## Author

**Utkarsh Vaishnav**

Computer Science Student
Monash University

## Academic Context

FIT3179 Data Visualisation
Monash University

## Note

This project was developed for academic purposes to demonstrate data visualisation, dashboard design, and analytical storytelling using Australian seafood industry data.
