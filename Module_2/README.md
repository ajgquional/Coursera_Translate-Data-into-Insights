# Module 2: Explore raw data

Finding stories in data using EDA is all about organizing and interpreting raw data. Python can help you do this quickly and effectively. You’ll learn how to use Python to perform the EDA practices of discovering and sculpting.

## Lesson objectives
* Identify ethical issues that may come up during the data “discovering” practice of EDA
* Use Python to merge or join data based on defined criteria
* Use Python to sort and/or filter data
* Use relevant Python libraries for cleaning raw data
* Recognize opportunities for creating hypotheses based on raw data
* Recognize when and how to communicate status updates and questions to key stakeholders
* Apply Python tools to examine raw data structure and format.
* Use the PACE workflow to understand whether given data is adequate and applicable to a data science project
* Differentiate between the common formats of raw data sources (json, tabular, etc.) and data types

# About the files

* This part of the repository contains several annotated guides (as Jupyter Notebooks) for the module about the "discovering" and "structuring" phases of EDA (Exploratory Data Analysis).

* The annotated guide on "EDA using basic data functions with Python" uses a dataset named ```eda_using_basic_data_functions_in_python_dataset1.csv```; however, the dataset is too large to be uploaded (101 MB). Should the dataset is needed to be downloaded, note that it came from ```bigquery-public-data.noaa_lightning.lightning_strikes`` public data table (thus, it can be queried in BigQuery). Additional details about the dataset:
  * It contains cloud-to-ground lightning strike information collected by Vaisala's National Lightning Detection Network (NLDN) and aggregated into 0.1° tiles by the National Centers for Environmental Information. This means that all the daily strikes within 0.1° latitude x 0.1° longitude are summed and assigned to a set of geographic coordinates that represents the center of the 0.1° "square" area. One thing to keep in mind as you explore this data is that, because circles of latitude become shorter the farther they are from the equator, the area encompassed by the tiles becomes smaller the farther north the tiles are located. For example, tiles at 50°N are approximately 7 km x 11 km, while tiles at 20°N are approximately 10 km x 11 km—nearly 43% larger in area.
  * More information about the dataset can be obtained from this <a href="https://ghrc.nsstc.nasa.gov/uso/ds_docs/nldn/gai_dataset.html#">documentation</a>.  

* The activities (and exemplars) on "Discover what is in your dataset" and "Structure your data" uses the dataset named ```Unicorn_Companies.csv``` and it is uploaded here. The original data is taken from <a href="https://www.kaggle.com/datasets/mysarahmadbhat/unicorn-companies">Kaggle</a> (where additional documentation can also be found).

* The annotated guide on "Date string manipulations with Python" uses a dataset named ```eda_manipulate_date_strings_with_python.csv```; however, the dataset is too large to be uploaded (311 MB). This dataset is the same as the NOAA lightning strikes dataset used in the previous annotated guide, so should the dataset is needed to be downloaded, information about the dataset can be found above.

* The annotated guide on "EDA structuring with Python" uses two datasets named ```eda_structuring_with_python_dataset1.csv``` and ```eda_structuring_with_python_dataset2.csv```; however, the datasets are too large to be uploaded (101 MB and 210 MB, respectively). These datasets also came from the same NOAA lightning strikes dataset used in the previous annotated guides, so should the dataset is needed to be downloaded, information about the dataset can be found above.
