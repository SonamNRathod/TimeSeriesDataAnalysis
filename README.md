# TimeSeriesDataAnalysis

## Project Overview
This repo is related to time series data analysis for creating forecasting model.

## About data
This dataset contains global temperature compared to the long-term average for each month and for different seasons. The data spans several decades and provides insights into temperature changes over time.

## Data Dictionary

This section describes each column in the dataset:

| **Column Name** | **Description**                                                                 | **Data Type** | **Units**                     |
|-----------------|---------------------------------------------------------------------------------|---------------|--------------------------------|
| `Year`          | Year of the recorded data.                                                       | Integer       | Year (e.g., 1880, 1881)        |
| `Jan`           | Temperature anomaly in January compared to the long-term average.                | Float         | Degrees Celsius                |
| `Feb`           | Temperature anomaly in February compared to the long-term average.               | Float         | Degrees Celsius                |
| `Mar`           | Temperature anomaly in March compared to the long-term average.                  | Float         | Degrees Celsius                |
| `Apr`           | Temperature anomaly in April compared to the long-term average.                  | Float         | Degrees Celsius                |
| `May`           | Temperature anomaly in May compared to the long-term average.                    | Float         | Degrees Celsius                |
| `Jun`           | Temperature anomaly in June compared to the long-term average.                   | Float         | Degrees Celsius                |
| `Jul`           | Temperature anomaly in July compared to the long-term average.                   | Float         | Degrees Celsius                |
| `Aug`           | Temperature anomaly in August compared to the long-term average.                 | Float         | Degrees Celsius                |
| `Sep`           | Temperature anomaly in September compared to the long-term average.              | Float         | Degrees Celsius                |
| `Oct`           | Temperature anomaly in October compared to the long-term average.                | Float         | Degrees Celsius                |
| `Nov`           | Temperature anomaly in November compared to the long-term average.               | Float         | Degrees Celsius                |
| `Dec`           | Temperature anomaly in December compared to the long-term average.               | Float         | Degrees Celsius                |
| `J-D`           | Average temperature anomaly from January to December in that year.               | Float         | Degrees Celsius                |
| `D-N`           | Average temperature anomaly from December of the previous year to November.      | Float         | Degrees Celsius                |
| `DJF`           | Average temperature anomaly for December, January, and February (winter months). | Float         | Degrees Celsius                |
| `MAM`           | Average temperature anomaly for March, April, and May (spring months).           | Float         | Degrees Celsius                |
| `JJA`           | Average temperature anomaly for June, July, and August (summer months).          | Float         | Degrees Celsius                |
| `SON`           | Average temperature anomaly for September, October, and November (fall months).  | Float         | Degrees Celsius                |

## Data Collection Methodology

The data was collected from a reliable global temperature monitoring service and reflects monthly and seasonal temperature anomalies. These anomalies are calculated based on the difference between the monthly/seasonal temperature and the long-term average for that same month or season. The data spans from 1880 onward and is updated annually.

## Why This Dataset?

This dataset is intriguing because it provides a long-term view of global temperature trends, allowing us to see changes in the climate over time. It is essential for analyzing global warming and climate change impacts, which are among the most pressing issues of our time.
  
## Data Collection Methodology
The data comes from the NASA GISS Surface Temperature Analysis (GISTEMP v4). This datasets are tables of global and hemispheric monthly means and zonal annual means. They combine land-surface, air and sea-surface water temperature anomalies (Land-Ocean Temperature Index, L-OTI). The values in the tables are deviations from the corresponding 1951-1980 means.
