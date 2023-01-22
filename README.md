# Argonne National Laboratory 60 meter Meteorological Tower

This repository covers data investigation, analysis, quality control, and cataloging for the ANL 60m Meteorological Tower.

## Motivation

As analysis of the 40+ years of meteorolgical data from the ANL Met Tower increases, a repository to hold individual contributions was needed. The aim of this repository is to hold all central quality control, analysis and cataloging for all researchers conducting analysis into the data.  

## Authors

[First Author](@jrobrien91), [Second Author](@mtuftedal)

### Contributors

<a href="https://github.com/EVS-ATMOS/atmos-tower/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=EVS-ATMOS/atmos-tower" />
</a>

### Running on Your Own Machine
If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "atmos-tower" with the title of your cookbooks)   

1. Clone the `https://github.com/EVS-ATMOS/atmos-tower/` repository:

   ```bash
    git clone https://github.com/EVS-ATMOS/atmos-tower/
    ```  
1. Move into the `atmos-tower` directory
    ```bash
    cd atmos-tower
    ```  
1. Create and activate your conda environment from the `environment.yml` file
    ```bash
    conda env create -f environment.yml
    conda activate atmos-tower
    ```  
1.  Move into the `notebooks` directory and start up Jupyterlab
    ```bash
    cd notebooks/
    jupyter lab
    ```
