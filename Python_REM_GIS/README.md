# Relative Elevation Model: Mississippi River

## Overview
This project aims to create a detailed Relative Elevation Model (REM) of the Mississippi River, utilizing Digital Elevation Model (DEM) data. The analysis provides insights into the river's geological history, flood patterns, and the impact of human activities on its ecosystem.

## Project Structure
- **Data**: Contains the DEM raster file used for analysis.
- **Notebooks**: Jupyter notebooks that contain the code and analysis for creating the REM.

## Installation
To run this project, you need to have Python installed along with the required packages. You can install the necessary packages using pip:



## Usage
1. **Download DEM Data**: Obtain the DEM data in `.tif` format and place it in the `Data` directory.
   
2. **Run the Notebook**: Open the Jupyter notebook `rem-in-xarray-tutorial.ipynb` and execute the cells sequentially. The notebook includes:
   - Installation of required packages.
   - Loading and processing the DEM data.
   - Clipping the DEM to focus on the area of interest.
   - Fetching coordinates of the Mississippi River.
   - Interpolating elevation values and creating the REM.
   - Visualizing the DEM and REM.

3. **Visualizations**: The notebook provides visualizations of the DEM and REM, allowing for a better understanding of the elevation patterns along the Mississippi River.

## Key Functions
- **Clipping the DEM**: The DEM is clipped to a specified area of interest using GeoJSON geometries.
- **Coarsening the DEM**: The resolution of the DEM is reduced for smoother visualization.
- **Interpolation**: Elevation values are interpolated to create a continuous surface.
- **Visualization**: The REM is visualized using hillshading techniques and color maps.


## Acknowledgments
- Credits: [Dahn](https://twitter.com/DahnJahn)