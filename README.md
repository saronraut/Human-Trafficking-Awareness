# project-one

This is the first project for the Data Analytics Boot Camp.
The members of this project team are: Elizabeth Harrison,  Lisa Jemmings, Shirley Limburg, Saron Raut, Mara Schemel, and Sumit Patel

The folder named 'data' contains the original data files.
The folder named 'cleanData' contains cleaned data files.
    The file evaluating_data.ipynb was used during the initial exploration of the data.
    The file Data_Cleaning.ipynb was used for the final data cleaning, merging, and exporting.

Project-one_completed contains our group presentation and Write up 
    Human Trafficking - Data Analysis.pptx
        Contains audio recording from class presentation 
    Project 1 Write Up - Human Trafficking.docx
        Contains descriptive analysis on our project. 

Our group write-up/final analysis can be found in file:

Saron's folder contains data analysis and visualizations based on Recruiter Relationship and Age Group:
- Saron-trafficking.ipynb MAIN NOTEBOOK. all data used for the project. 
- png folder has .png for all the visual graphs
- cleanData is the copy of cleanData from main branch
- Test_group.ipynb is test notebook for code snippets
- Nested_Pie_Chart-Copy1.ipynb collaborative effort with Liz to creating nesting pie chart
- Nested_Pie_Chart.ipynb created as a template collaborative effort with Liz
- color_liz.xlsx excel data on colors assigned for nesting Pie Chart


Liz's folder contains data analysis and visualizations based on Citizenship Country and Exploitation Country:

- Data_Exploration.ipynb --> this is the starting point of my data exploration and visualization and is a working file that was subsequently organized into the following two files:
- Where From Organized.ipynb --> All the code pertaining to trafficking victims area of citizenship
- Exploited.ipynb --> All the code pertaining to trafficking victims area of exploitation


Mara's folder contains data analysis and map visulalizations supporting the findings from Liz

Sumit folder contains data analysis and visualizations based on labor and sexual exploitation.

Lisa's folder contains data analysis and visualizations including data for population density

Shirley's folder contains data analysis and visualizations including data for economic factors and government type


In order to successfully run the files in the folder named 'Mara':

- You will need a google API key. Place your API key in the config.py file

- You will also need to have plotly installed:

    Use this command to install plotly: pip install plotly==4.12.0
    
    Use this command to provide Jupyter Notebook Support for plotly: pip install "notebook>=5.3" "ipywidgets>=7.2"
    
    Or visit: https://plotly.com/python/getting-started/
    
- For more information on how to use choropleth maps from plotly visit: https://plotly.com/python/choropleth-maps/
    

Data Sources:
- https://worldpopulationreview.com/state-rankings/human-trafficking-statistics-by-state
- https://www.dhs.gov/sites/default/files/publications/20_0115_plcy_human-trafficking-forced-labor-child-exploit-strategy.pdf 
- https://www.dhs.gov/sites/default/files/publications/4146_CombattingHumanTraffickingThroughSocialScience.pdf
- https://data.worldbank.org/ , [10,2020]
- https://worldpopulationreview.com/ , [10, 2020]
- https://www.ctdatacollaborative.org  , [10, 2020]
