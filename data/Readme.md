# Dataset Description

## Introduction

The dataset provides an overview of global energy dynamics. It shows different variables related to energy consumption, production, and environmental impact. For example, the names of several countries across the world,the year the data was recorded for that particular country, population, GDP, biofuel consumption, coal usage, gas consumption, nuclear power, oil consumption, hydropower, low-carbon energy, renewables (solar and wind power), and electricity generation. The dataset also describes diverse metrics such as per capita measures, annual changes, and percentage shares, offering valuable insights in the global use energy. As the OWID site explains, the "complete Energy dataset is a collection of key metrics maintained by Our World in Data. It is updated regularly and includes data on energy consumption (primary energy, per capita, and growth rates), energy mix, electricity mix and other relevant metrics" (Rosado et.al, 2023).

## Dataset description of variables 

Detailed description of each variable in the dataset. 

| Variable Name                     | Description                                      | Frequency     | Range           | Unit                   | Type                    |
| --------------------------------- | ------------------------------------------------ | ------------- | --------------- | ---------------------- | ----------------------- |
| country                           | Country name                                    | -             | -               | -                      | String                 |
| year                              | Year of observation                             | Annual        |  -              | -                      | Integer                |
| iso_code                          | ISO country code                                | -             | -               | -                      | String                 |
| population                        | Total population                                | Annual        | -               | -                      | Integer                |
| gdp                               | Gross Domestic Product                          | Annual        | -               | Currency (e.g., USD)   | Numeric                |
| biofuel_cons_change_pct           | Percentage change in biofuel consumption        | Annual        | -               | Percentage             | Numeric                |
| biofuel_cons_change_twh           | Change in biofuel consumption (TWh)             | Annual        | -               | Terawatt-hour          | Numeric                |
| biofuel_cons_per_capita           | Biofuel consumption per capita                 | Annual        | -               | -                      | Numeric                |
| biofuel_consumption               | Total biofuel consumption                       | Annual        | -               | -                      | Numeric                |
| biofuel_elec_per_capita           | Biofuel electricity per capita                 | Annual        | -               | -                      | Numeric                |
| biofuel_electricity               | Total biofuel electricity generation           | Annual        | -               | -                      | Numeric                |
| biofuel_share_elec                | Biofuel share in electricity generation        | Annual        | -               | Percentage             | Numeric                |
| biofuel_share_energy              | Biofuel share in total energy consumption       | Annual        | -               | Percentage             | Numeric                |
| carbon_intensity_elec             | Carbon intensity of electricity generation      | Annual        | -               | Grams CO2 per kWh      | Numeric                |
| coal_cons_change_pct              | Percentage change in coal consumption          | Annual        | -               | Percentage             | Numeric                |
| coal_cons_change_twh              | Change in coal consumption (TWh)               | Annual        | -               | Terawatt-hour          | Numeric                |
| coal_cons_per_capita              | Coal consumption per capita                   | Annual        | -               | -                      | Numeric                |
| coal_consumption                  | Total coal consumption                         | Annual        | -               | -                      | Numeric                |
| coal_elec_per_capita              | Coal electricity per capita                    | Annual        | -               | -                      | Numeric                |
| coal_electricity                  | Total coal electricity generation              | Annual        | -               | -                      | Numeric                |
| coal_prod_change_pct              | Percentage change in coal production           | Annual        | -               | Percentage             | Numeric                |
| coal_prod_change_twh              | Change in coal production (TWh)                | Annual        | -               | Terawatt-hour          | Numeric                |
| coal_prod_per_capita              | Coal production per capita                    | Annual        | -               | -                      | Numeric                |
| coal_production                   | Total coal production                          | Annual        | -               | -                      | Numeric                |
| coal_share_elec                   | Coal share in electricity generation           | Annual        | -               | Percentage             | Numeric                |
| coal_share_energy                 | Coal share in total energy consumption          | Annual        | -               | Percentage             | Numeric                |
| electricity_demand                | Total electricity demand                      | Annual        | -               | -                      | Numeric                |
| electricity_generation            | Total electricity generation                  | Annual        | -               | -                      | Numeric                |
| electricity_share_energy          | Electricity share in total energy consumption   | Annual        | -               | Percentage             | Numeric                |
| energy_cons_change_pct            | Percentage change in total energy consumption  | Annual        | -               | Percentage             | Numeric                |
| energy_cons_change_twh            | Change in total energy consumption (TWh)       | Annual        | -               | Terawatt-hour          | Numeric                |
| energy_per_capita                 | Total energy consumption per capita            | Annual        | -               | -                      | Numeric                |
| energy_per_gdp                    | Energy consumption per unit of GDP             | Annual        | -               | -                      | Numeric                |
| fossil_cons_change_pct            | Percentage change in fossil fuel consumption   | Annual        | -               | Percentage             | Numeric                |
| fossil_cons_change_twh            | Change in fossil fuel consumption (TWh)        | Annual        | -               | Terawatt-hour          | Numeric                |
| fossil_elec_per_capita            | Fossil fuel electricity per capita             | Annual        | -               | -                      | Numeric                |
| fossil_electricity                | Total fossil fuel electricity generation      | Annual        | -               | -                      | Numeric                |
| fossil_energy_per_capita           | Fossil fuel energy consumption per capita     | Annual        | -               | -                      | Numeric                |
| fossil_fuel_consumption           | Total fossil fuel consumption                  | Annual        | -               | -                      | Numeric                |
| fossil_share_elec                 | Fossil fuel share in electricity generation    | Annual        | -               | Percentage             | Numeric                |
| fossil_share_energy               | Fossil fuel share in total energy consumption   | Annual        | -               | Percentage             | Numeric                |
| gas_cons_change_pct               | Percentage change in gas consumption           | Annual        | -               | Percentage             | Numeric                |
| gas_cons_change_twh               | Change in gas consumption (TWh)                | Annual        | -               | Terawatt-hour          | Numeric                |
| gas_consumption                   | Total gas consumption                           | Annual        | -               | -                      | Numeric                |
| gas_elec_per_capita               | Gas electricity per capita                     | Annual        | -               | -                      | Numeric                |
| gas_electricity                   | Total gas electricity generation               | Annual        | -               | -                      | Numeric                |
| gas_energy_per_capita              | Gas energy consumption per capita             | Annual        | -               | -                      | Numeric                |
| gas_prod_change_pct               | Percentage change in gas production            | Annual        | -               | Percentage             | Numeric                |
| gas_prod_change_twh               | Change in gas production (TWh)                 | Annual        | -               | Terawatt-hour          | Numeric                |
| gas_prod_per_capita               | Gas production per capita                      | Annual        | -               | -                      | Numeric                |
| gas_production                    | Total gas production                            | Annual        | -               | -                      | Numeric                |
| gas_share_elec                    | Gas share in electricity generation            | Annual        | -               | Percentage             | Numeric                |
| gas_share_energy                  | Gas share in total energy consumption           | Annual        | -               | Percentage             | Numeric                |
| greenhouse_gas_emissions          | Total greenhouse gas emissions                 | Annual        | -               | Grams CO2 equivalent  | Numeric                |
| hydro_cons_change_pct             | Percentage change in hydro consumption         | Annual        | -               | Percentage             | Numeric                |
| hydro_cons_change_twh            


## Dataset CSV - [owed-energy-data.csv](owid-energy-data.csv)

This file is the complete dataset. Due to its size, no preview is available in Github but it can still be downloaded from this link.

## References

Ritchie, Hannah, Pablo Rosado, and Max Roser. 2023. "Energy." OurWorldInData.org. Retrieved from 'https://ourworldindata.org/energy' [Online Resource].