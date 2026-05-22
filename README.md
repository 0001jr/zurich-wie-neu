#### Züri wie neu

This project examines how citizen-reported urban issues in Zurich are distributed across neighborhoods and how their intensity, development, and categories have changed between 2014 and 2025. It combines reports of issues with infrastructure, statistical neighbourhood boundaries, and neighbourhood population data to identify where urban problems are most concentrated and how they evolve over time.






#### Datasets

The datasets are form https://data.stadt-zuerich.ch/dataset: 

- Reports from Züri wie neu: https://data.stadt-zuerich.ch/dataset/geo_zueri_wie_neu

- Statistische Quartiere (Neighborhoods): https://data.stadt-zuerich.ch/dataset/geo_statistische_quartiere

- Population by neighbourhood https://data.stadt-zuerich.ch/dataset/bev_bestand_jahr_quartier_od3240

The datasets need to contain data from 2014-2025 (full years).






#### Repository structure

data/raw/: raw datasets
data/processed/: processed datasets
notebooks/: Jupyter notebook of Zurich wie neu
outputs/maps/: maps exported from the notebook






#### Setup

The analysis was created using the sdszuri-env conda environment.
The complete environment can be recreated using the provided environment.yml file.

Required Python packages:

jupyterlab ipykernel
geopandas 
pandas 
matplotlib 
mapclassify






#### Execution Order

Run the notebook zuri-wie-neu: https://github.com/0001jr/zurich-wie-neu/blob/main/notebooks/zuri-wie-neu.ipynb

Execute from top to bottom.
