# Screening Project

## Description

This script addresses the data analysis of screening libraries performed using a Molecular Devices plate reader. The program automatically generates the following directories in the working directory:

- **Results**: Contains analysis results in different formats.
  - **Group By Assay**: This directory will include Excel (`.xlsx`) files with all TAI analyses organized by **assay**.
  - **Group By Assay and Plate**: This directory will contain Excel (`.xlsx`) files with TAI data organized by both **assay and plate**.
  - **Comparisons**: This directory contains different comparisons made among assays.
  
- **Parental Diagnosis**: `.xlsx` file with mean, standard deviation, and selected parental values.
  
- **Relevant Data Frames**: Includes the following files:
  - **Assay_code.xlsx**: Contains codes of the detected assays.
  - **Plate_codes.xlsx**: Contains codes of the plates.

## Project Structure

- `data/`: Contains data files.
  - `example_data.csv`: Example data file on which the program runs.
  
- `notebooks/`: Contains Jupyter Notebook files.
  - `your_notebook.ipynb`: Your Jupyter Notebook file with the analysis.
  
- `src/`: Contains Python scripts.
  - `script.py`: Additional Python scripts (if any).
  
- `Results/`: Automatically generated directory with subdirectories.
  - `Group By Assay/`
  - `Group By Assay and Plate/`
  - `Comparisons/`
  
- `Parental Diagnosis/`: Contains the `.xlsx` file for parental diagnosis.
  
- `Relevant Data Frames/`: Contains files with assay and plate codes.
  - `Assay_code.xlsx`
  - `Plate_codes.xlsx`
  
- `environment.yml`: Environment specifications file.

- `README.md`: This file.

- `.gitignore`: File to exclude unwanted files from the repository.