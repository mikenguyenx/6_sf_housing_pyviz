# SF Housing Visual Analysis

Proptech, the application of technology to real-estate markets, is an innovative domain in the fintech industry. A proptech company has is looking to launch a one-click service for people to buy properties and then rent them. The company wants to have a trial of this offering in the San Francisco real-estate market. If the service proves popular, they can then expand to other markets.

This Jupyter notebook contains the analysis of the housing rental market data for San Francisco. The analysis uses data visualization techniques, including aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market that are viable investment opportunities.


## Technologies

Programming Language: Python 3.7.13

Interactive Development Environment: JupyterLab


Libraries: 
- Pandas - A Python library that is used for data manipulation, analysis, and visualization. 
- Pathlib - A Python module that provides an object-oriented interace to working with files & directories.
- PyViz - A Python-based open-source visualization framework that provides a suite of tools for creating interactive visualizations of data, including several libraries like hvPlot and GeoViews.
- HvPlot - A Python library for creating interactive plots using the HoloViews library and Bokeh visualization library. 
- Warnings - A Python library that provides a way to handle warning messages that may occur during the execution of a program.

Operating System(s):  Any operating system that supports Python, including Windows & macOS.

## Installation Guide

To run this analysis, make sure you install the necessary dependencies:

1. Install Python: https://www.python.org/downloads/
2. Install and run Jupyter Lab:  https://jupyter.org/install
3. Install the necessary libraries using pip, the package installer for Python:
```
pip install pandas pathlib 
```
4. Install the PyViz packages by using the conda install command as follows:
```
conda install -c pyviz hvplot geoviews
```
The following image shows the packages to be installed:

![hvplot_geoviews1](hvplot_geoviews1.png)

5. Confirm the installation of all the PyViz packages by running the following commands:
```
 conda list hvplot
 conda list geoviews
```
The following image shows the responses, which list the installed packages.

IMPORTANT
Make sure to use hvPlot version 0.7.0 or later.

![hvplot_geoviews2](hvplot_geoviews2.png)

6. Clone the repository: `git clone "https://github.com/mikenguyenx/6_sf_housing_pyviz"` using git or download the ZIP file and extract it to a local directory.


## Usage

To run the script for the Fund Portfolio Risk Return Analysis:

1. Open a terminal or command prompt and navigate to the directory with the analysis.
1. Launch Jupyter Lab: jupyter lab
2. Open `san_francisco_housing.ipynb` in Jupyter Lab.
3. Run the code cells by clicking on the run button or by pressing the `Shift + Enter` key combination to load and preprocess the data, and generate visualizations
4. The script uses Pandas to read CSV data into the Jupyter notebook file for analysis through interactive visualizations and geospatial analysis to find properties in the San Francisco market that are viable investment opportunities using the PyViz framework and HvPlot libraries.

Below are screenshots of examples of results from the analysis:

### Housing Units Visualization 

![housing_units](housing_units_bar.png)

### Interactive Line Plot - Average Sale Prices & Gross Rent

![interactive_line_plot](interactive_line_plot.png)

### Interactive Neighborhood Map (Geospatial Analysis)

![interactive_geo_map](interactive_geo_map.png)


## Contributors

Mike Nguyen

Email: nguyen.mikeq@gmail.com

LinkedIn: https://www.linkedin.com/in/mike-nguyen-6899554/

## License

MIT

