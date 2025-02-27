# SERIE-TEMPORELLE-MOSEF
This is a time series project that was realized during the Master 2 MoSEF. The goal is to predict the height of waves in Nazaré, Portugal during the period 2016-2017.

## To download the data from Copernicus:
- Dataset: https://cds.climate.copernicus.eu/datasets/sis-ocean-wave-timeseries?tab=overview
  + Variables: Mean wave direction, Mean wave period, Peak wave period, Significant wave height
  + Experiment: ERA5 reanalysis
  + Year: 2016, 2017
- How to download with API: https://ecmwf-projects.github.io/copernicus-training-c3s/cds-tutorial.html

## Installation
1. Clone GitHub :

    ```bash
    git clone https://github.com/vonguyenthaonhi/SERIE-TEMPORELLE-MOSEF.git
    cd SERIE-TEMPORELLE-MOSEF
    ```

2. Create a virtual environment :

    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment :

    - **Windows** :

        ```bash
        .\venv\Scripts\Activate
        ```

    - **Linux/Mac** :

        ```bash
        source venv/bin/activate
        ```

4. Install required packages

    ```bash
    pip install -r requirements.txt
    ```
    
## Authors

- [Vo Nguyen Thao Nhi](https://github.com/vonguyenthaonhi)
- [Tarvedian Mariam](https://github.com/Maro18287)
- [Vazelle Lucas](https://github.com/lucasvazelle)
