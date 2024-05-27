# Project 3: Opdracht - statistiek - visualisatie (Gilles Servais)

Welcome to the Project "Opdracht - statistiek - visualizatie". This project is designed to do some statistical analysis on provided data.

This project has two parts:

1. Productieproces

This simulates the production of a variabel amount of days. The model is created on historical data "BRU". Also "STO" could be used.
Two model are demonstrated and compared to each other.

2. Autoproductie

Some analyses is done on the dataset cars.csv.
Questions are being discussed and answers provided by means of analyzing the data.

## Installation

### Installing the Environment

1. Clone this repository to your local machine:
   ```sh
   git clone https://github.com/HubGilles/Project3-statistiek
2. Navigate to the project directory:
    ```sh
    cd project-name
3. Create a new conda environment from the provided YAML file:
    ```sh
    conda env create -f Project3.yml
4. Activate the newly created conda environment:
    ```sh
    conda activate .Project3
### Running the Project
After activating the conda environment, you can run the project using the following steps:

1. Navigate to the project directory:

    ```sh
    cd /path/to/your/project
2. Run the Jupyter Notebook:
    ```sh
    Project3_oplossing.ipynb
3. Make sure to refer to the correct directory (where BRU and STO data is saved) for Part 1:
    ```sh 
    BRU_loc = "/Users/gillesservais/Documents/Syntra/Project3/Opdracht - statistiek - visualizatie/data_productie/daily_production/BRU"
    
    STO_loc = "/Users/gillesservais/Documents/Syntra/Project3/Opdracht - statistiek - visualizatie/data_productie/daily_production/STO"

4. For Part 2, make sure to correct the filepath to the cars.csv file:
    ```sh 
    cars_csv = "/Users/gillesservais/Documents/Syntra/Project3/Opdracht - statistiek - visualizatie/cars.csv"

