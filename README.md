# housing-25
Central Maine Growth Council (CMGC) has created the following analytical tool to create visualizations and conduct seasonal adjustments to housing data obtained from Realtor.com. This repo contians the .ipynb that takes in a valid dataset and provides the outputs based on the variables configured. 

“This project is provided as-is for research, educational, advocacy, and commercial use. The authors and affiliated nonprofit assume no responsibility for outcomes derived from its use.”

# Housing Data Analysis Notebook

## Created by: Central Maine Growth Council

## Data Source
[Realtor.com Research Data](https://www.realtor.com/research/data/)

This notebook analyzes housing market metrics for a specified ZIP code, comparing against state and national trends. It produces:

- Seasonal adjustment analysis using Prophet  
- Geographic comparison plots (ZIP vs State vs National)  
- Yearly summary tables  

## Requirements

1. This is a Python 3–based Jupyter Notebook and requires Python to be installed along with JupyterLab or Jupyter Notebook.  
   - See the provided link above for installation guidance.

2. The following Python libraries are required:
   - `pandas`
   - `numpy`
   - `math`
   - `os`
   - `warnings`
   - `prophet`
   - `plotly`
   - `kaleido`

3. Google Chrome must be installed.

## Usage

1. Edit the **Configuration** cell with your desired settings, including the file path.
3. Run all cells (`Cell → Run All`).  
4. Review the outputs in the specified directories.
