# skforecast-datasets

This repository contains datasets used in the skforecast library. It also contains datasets used in related tutorials.

## Datasets

### h2o

+ url: https://raw.githubusercontent.com/JoaquinAmatRodrigo/skforecast/master/data/h2o.csv
+ sep: ','
+ index_col: fecha
+ date_format: %Y-%m-%d
+ freq: MS
+ description: Monthly expenditure ($AUD) on corticosteroid drugs that the Australian health system had between 1991 and 2008.
+ source: Hyndman, R.J., & Athanasopoulos, G. (2021) Forecasting: principles and practice, 3rd edition, OTexts: Melbourne, Australia. OTexts.com/fpp3.

### items_sales

+ url: https://raw.githubusercontent.com/JoaquinAmatRodrigo/skforecast/master/data/simulated_items_sales.csv
+ sep: ','
+ index_col: date
+ date_format: %Y-%m-%d
+ freq: D
+ description: Simulated time series for the sales of 3 different items.
+ source: Simulated data

### air_pollution

+ url: https://raw.githubusercontent.com/JoaquinAmatRodrigo/skforecast/master/data/guangyuan_air_pollution.csv
+ sep: ','
+ index_col: date
+ date_format: %Y-%m-%d
+ freq: D
+ description:
+ source:

### fuel_consumption

+ url: https://raw.githubusercontent.com/JoaquinAmatRodrigo/Estadistica-machine-learning-python/master/data/consumos-combustibles-mensual.csv
+ sep: ','
+ index_col: Fecha
+ date_format: %Y-%m-%d
+ freq: MS,
+ description: Monthly fuel consumption in Spain from 1969-01-01 to 2022-08-01.
+ source: Obtained from Corporación de Reservas Estratégicas de Productos Petrolíferos y Corporación de Derecho Público tutelada por el Ministerio para la Transición Ecológica y el Reto Demográfico. https://www.cores.es/es/estadisticas

## air_quality_valencia

+ url: https://raw.githubusercontent.com/JoaquinAmatRodrigo/Estadistica-machine-learning-python/master/data/air_quality_valencia.csv
+ sep: ','
+ index_col: datetime
+ date_format: date_format: %Y-%m-%d %H:%M:%S,
+ freq: H,
+ description: Hourly measures of several air quimical pollutant (pm2.5, co, no, no2, pm10, nox, o3, so2) at Valencia city.
+ source: Red de Vigilancia y Control de la Contaminación Atmosférica, 46250054-València - Centre, https://mediambient.gva.es/es/web/calidad-ambiental/datos-historicos

### web_visits
+ url: (
+     https://raw.githubusercontent.com/JoaquinAmatRodrigo/Estadistica-machine-learning-python/
+     master/data/visitas_por_dia_web_cienciadedatos.csv
+ ),
+ sep: ,,
+ index_col: date,
+ date_format: %Y-%m-%d,
+ freq: 1D,
+ description: (
+     Daily visits to the cienciadedatos.net website registered with the google 
+     analytics service.
+ )
+ },
+ bike_sharing
+ url: (
+     https://raw.githubusercontent.com/JoaquinAmatRodrigo/Estadistica-machine-
+     learning-python/master/data/bike_sharing_dataset_clean.csv
+ ),
+ sep: ,,
+ index_col: date_time,
+ date_format: %Y-%m-%d %H:%M:%S,
+ freq: H,
+ description: (
+     """
+     Hourly usage of the bike share system in the city of Washington,
+     D.C. during the years 2011 and 2012. In addition to the number of
+     users per hour, information about weather conditions and holidays
+     is available. The original data was obtained from:
+     Fanaee-T,Hadi. (2013). Bike Sharing Dataset. UCI Machine Learning
+     Repository. https://doi.org/10.24432/C5W894.
+     """
+ )
+ },
+ store_item_demand
+ url: (
+     https://raw.githubusercontent.com/JoaquinAmatRodrigo/Estadistica-machine-
+     learning-python/master/data/bike_sharing_dataset_clean.csv
+ ),
+ sep: ,,
+ index_col: date_time,
+ date_format: %Y-%m-%d %H:%M:%S,
+ freq: H,
+ description: (
+     """
+     This dataset contains 913,000 sales transactions from 2013-01-01
+     to 2017-12-31 for 50 products (SKU) in 10 stores. The original data
+     was obtained from:
+     inversion. (2018). Store Item Demand Forecasting Challenge. Kaggle.
+     https://kaggle.com/competitions/demand-forecasting-kernels-only
+     """
+ )
+ ```