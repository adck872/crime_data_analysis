UK Crime Analysis- Exploratory Data analysis

Project Overview--------------------------------------------------------------------------------------------------------- this project provides an exploratory analysis of crime across four uk police forces for Nadine to understand how crime patterns can influence location desirability and using the data the analysis identifies areas that appear safer or riskier, how crime varies over time and which police forces should be prioritised for deeper study in the next stage

Data source --------------------------------------------------------------------------------------------------------------

data obtained from the official Police open data platform https://data.police.uk/data/

population data https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/adhocs/3194populationestimatesforpoliceforceareasinenglandandwalesbysingleyearofageandsexmid1991tomid2024

Project structure---------------------------------------------------------------------------------------------------------

Work_statement.pdf - work statement of the project Eda report.pdf - report with all key findings and relevant analysis Preprocessing.ipynb - pre-processing notebook of all the data to be analysed Analysis.ipynb - analysis notebook of all charts explored with explanations data - all data containing population data and police force data map-data - containing jseon file for maps population_cv - cleaned population data population.xlxl - excel pre-processing file policeforceareas2024.csv - police force data cleaned flowchart.png- flowchart of preprocessing taskS

technologies used----------------------------------------------------------------------------------------------------------- pandas matplotlib seaborn folium - must be installed geopandas- must be installed

how to run project-----------------------------------------------------------------------------------------------------------

preprocessing.ipynb

ctrl shift runs through all cells

analysis.ipynb

import folium and geopandas ( if using anaconda must go on anaconda prompt and install modules there) pip install folium pip install geopandas

ctrl shift run all cells

note: the maps have been uncommented as it takes a lot of memory space uncomment the map to display each map one by one to see the zoomable maps in notebook.

GitHub link------------------------------------------------------------------------------------------------------------------ https://github.com/adck872/crime_data_analysis

Trello board link------------------------------------------------------------------------------------------------------------ https://id.atlassian.com/invite/p/goal?id=_DAhMT48RRWDeMoiL0js5w
