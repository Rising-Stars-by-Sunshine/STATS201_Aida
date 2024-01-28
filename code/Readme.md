# Data Query

## Description

**Step 1**

This section describes the data query and data analysis process.

The data was downloaded from Our World in Data, a scientific online publication focusing on large global problems such as poverty, disease, hunger, climate change, war, existential risks, and inequality (Roser, n.d.). This specific dataset was found under the topic of [Energy](https://ourworldindata.org/energy). The following is the description of the page:

> The world lacks a safe, low-carbon, and cheap large-scale energy infrastructure.
>
> Until we scale up such an energy infrastructure, the world will continue to face two energy problems: hundreds of millions of people lack access to sufficient energy, and the dominance of fossil fuels in our energy system drives climate change and other health impacts such as air pollution.
>
> To ensure everyone has access to clean and safe energy, we need to understand energy consumption and its impacts around the world today and how this has changed over time.
>
> On this page, you can find all our data, visualizations, and writing relating to energy. 
(Rosado, et.al, 2023)

<p align="center">
  <kbd>
    <img src="data_site.png" alt="OWID"/>
  </kbd>
</p>

*Image created by OWID*

**Step 2**

All code from Our World in Data is open-sourced under the MIT license and can be found on GitHub. Thus, I downloaded the data and codebook directly from their official [Github repository](https://github.com/owid/energy-data/blob/master/README.md). 

<p align="center">
  <kbd>
    <img src="data_github.png" alt="github"/>
  </kbd>
</p>

*Image created by OWID*

The data downloaded was already orginized in a CSV file.

**Step 3**

Looking at the data in the csv file, it is clear that the data needs to be cleaned to remove null values focusing on the research question at hand. For this, the plan is to use python libraries such as Pandas. 

# Data Visualization
The data visualization was done using the dash app. This [file](app.py) contians the code to run the interactive plot of a Time Series analysis of Energy Production including, total electricity generation, from fossil fuels, and from renewables. Below are the static plots of these variables throughout time for the US. The reason why only teh US is shown is because there are a lot of locations repreesnted in the dataset and the visualization of only one major power is enough to get an idea of waht the raw data shows. To interact with the plot, run the code on your local computer. 

<p align="left">
  <kbd>
    <img src="Energy_fossil.png" alt="dash"/>
  </kbd>
</p>

*Figure 1: Electricity produced in the US by Fossil Fuels thourhgout time. Image created with Dash app*

<p align="center">
  <kbd>
    <img src="Energy_renewables.png" alt="dash"/>
  </kbd>
</p>

*Figure 2: Electricity produced in the US by Renewable sources throughout time. Image created with Dash app*

<p align="right">
  <kbd>
    <img src="Energy_total_electricity.png" alt="dash"/>
  </kbd>
</p>

*Figure 3: Total Electricity produced in the US throughout time. Image created with Dash app*
