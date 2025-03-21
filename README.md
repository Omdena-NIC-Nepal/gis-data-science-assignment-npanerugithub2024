# GIS_Data_Science
## Assignment: GIS Data Science for Climate in Nepal
### Objective:
- The objective of this assignment is to assess your understanding and practical skills in GIS Data Science, specifically focusing on climate data analysis for Nepal. You will be required to perform data reading, visualization, and exploratory data analysis (EDA) tasks using Python.

### Steps to Complete the Assignment:
#### Setup Instructions:

- Clone the repository from GitHub Classroom.
    - git clone https://github.com/Omdena-NIC-Nepal/gis-data-science-assignment-npanerugithub2024.git
- Ensure Python environment is set up with necessary libraries (e.g., pandas, geopandas, matplotlib, seaborn).
#### Data Collection and Preparation:

- Data Source: Use climate-related GIS data for Nepal. You can use resources like NASA Earthdata, NOAA, or local government portals. ALternatively, you can also use the data here: https://github.com/Desmondonam/Nepal_Climate_change
- Data Reading: Read the GIS data into Python using geopandas or other relevant libraries.
    - The temperature data provided by Desmond through above link was used for this assignment.

### Data Visualization:

- Task: Visualize the GIS data to explore climate patterns in Nepal.
#### Required Visualizations: Include at least:
- A map showing temperature or precipitation trends over time.
- Any additional relevant visualizations that help interpret climate data.

#### Exploratory Data Analysis (EDA):

##### Tasks:
- Compute basic statistics (mean, median, min, max) of relevant climate variables.
- Identify any trends or patterns in the data using statistical summaries and visualizations.
- Discuss any observations or insights from your EDA process.

### Documentation:

### README File:
- Provide a clear explanation of the assignment objectives and tasks.
    The objective is to perform Exploratory Data Analysis (EDA) of climate data for Nepal using GIS tools and statistical methods, in order to understand spatial and temporal patterns of temperature or precipitation change between 2020 and 2050. Temperature data was chosen for this assignment.
    Tasks Completed:
    - Computed Basic Statistics (mean, median, min, max) for temperature in Nepal for the years 2020 and 2050.
    - Identified trends and patterns in temperature change over time using both statistical summaries and visualizations.
    - Discussed insights and observations based on data patterns

- Include instructions on how to set up the environment and run the Python scripts.
     - Created a virtual environment: python -m venv venv
     - Activate it: .\venv\Scripts\activate
     - Install all libraries using a text file named as requirements.txt: 
        - pandas
        - geopandas
        - matplotlib
        - seaborn
        - rasterio

- Document the data sources and any preprocessing steps taken.
     - Temperature data provided by Desmond was chosen.
     - Nepal's boundary was taken from a shapefile in the Shape_Data directory attached herewith this assignment and downloaded from Desmond's link.
     - The vector file was visualized to see what it contains. It was map of Nepal with all local units.
     - The content of vector file was printed and reviewed.
     - The shapefile was checked to see if there were any missing data.
     - Temperature data (raster data) was also taken from tif files in the nepal_climate_data directory attached herewith this assignment and    downloaded from Desmond's link.
     - The raster files were visualized to see the content of it.
     - The size of the raster file was checked.
     - A sample of this raster data was printed.
     - The meta data was printed for this raster.
     - The number of bands of this raster was checked and found to be 12 which corresponds to 12 months in a year.
     - The coordinate reference system was printed.


- Describe each visualization produced and its significance in understanding climate data for Nepal.

    The vector shapefile and raster TIFF files were integrated to visualize the temperature differences between 2020 and 2050. The resulting   comparative analysis revealed a clear and significant warming trend across the entire country. The side-by-side temperature maps and a temperature difference map highlighted consistent increases in temperatures, underscoring the impact of climate change over the three-decade period. 

    A line graph was also created comparing average monthly temperature trends for 2020 and 2050. Consistent increase in monthly temperatures in 2050 compared to 2020. The greatest temperature rise is noticeable during the pre-monsoon and fall season.

    These visualizations provide a compelling depiction of the escalating temperatures and their potential implications for Nepal's environment and ecosystems.

- Summarize your findings from the EDA process.

    The mean temperature increased by nearly 0.86 °C from 2020 to 2050, indicating a warming trend. Maximum temperature increased, showing hotter regions getting warmer in future projections. Minimum temperature also increased slightly, indicating that even the coldest areas may get relatively warmer by 2050. A slightly lower standard deviation in 2050 suggests temperatures may become more uniform across the country.

### Submission:

- Commit all your code, including Python scripts and README file, to the GitHub repository.
- Ensure that your repository is properly organized and well-documented.
## Deliverables:
- GitHub Repository:
    - Contains all necessary Python scripts, data files, and the README file.
- README File:
    - Clearly explains the assignment objectives, setup instructions, and tasks.
    - Documents data sources, preprocessing steps, and findings from EDA.
    - Provides insights gained from visualizations and analysis of climate data for Nepal.
##### Additional Notes:
- Evaluation Criteria: Your assignment will be evaluated based on clarity of documentation, correctness of code implementation, quality of visualizations, depth of EDA insights, and adherence to the assignment objectives.

- Resources: Utilize online resources, documentation of libraries (e.g., geopandas, matplotlib), and relevant tutorials to support your implementation.