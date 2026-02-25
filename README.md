# Housing Market Analysis and Visualization | Realtor.com Housing Data
Central Maine Growth Council (CMGC) has created the following analytical tool to create visualizations and conduct seasonal adjustments to housing data obtained from Realtor.com. This repo contians the .ipynb that takes in a valid dataset and provides the outputs based on the variables configured. 

“This project is provided as-is for research, educational, advocacy, and commercial use. The authors and affiliated nonprofit assume no responsibility for outcomes derived from its use.”

# Housing Data Analysis Notebook

## Created by: [Central Maine Growth Council](https://www.centralmaine.org/)

## Data Source
[Realtor.com Research Data](https://www.realtor.com/research/data/)

This notebook analyzes housing market metrics for a specified ZIP code, comparing against state and national trends. It produces:

- Seasonal adjustment analysis using [Facebook's Prophet Forecasting Model](https://facebook.github.io/prophet/) 
- Geographic comparison plots (ZIP vs State vs National)  
- Yearly summary tables  

## Requirements

1. This is a Python 3–based Jupyter Notebook and requires Python to be installed along with JupyterLab or Jupyter Notebook.  
   - See the provided link above for installation guidance.

2. The following Python libraries are require. These are provided in the requirements.txt file:
   - `pandas`
   - `numpy`
   - `math`
   - `os`
   - `warnings`
   - `prophet`
   - `plotly`
   - `kaleido`

3. Google Chrome must be installed.

## Set Up Instructions (Mac OS)
These are generic instructions. Please verify them and use at your own risk. These are common python and environment set up instructions for MacOS that you can find online.

### Python + JupyterLab Setup (macOS)

This guide covers installing Python on macOS, creating a virtual environment, installing JupyterLab and required libraries, and activating/deactivating the environment.

---

#### 1. Install Homebrew (if not already installed)
Homebrew is used to install and manage Python.

bash (terminal - you can search for it in your apps. Copy and paste the line below)

```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```

```brew --version```

#### 2. Install Python

Install the latest stable Python 3 release:

```brew install python```

Confirm installation:

```python3 --version```

```pip3 --version```

#### 3. Create Virtual Environment
This helps stabilize all the libraries used and ensure that other apps on your computer are not affected. This step will utilize the ```requirements.txt``` file so make sure to download it.

```python3 -m venv .venv```

```source .venv/bin/activate```

```pip install --upgrade pip```

```pip install -r requirements.txt```

```jupyter lab```

After this step, navigate in the application to the jupyter notebook file downloaded from this git.

#### Deactivating and Reactivating the Environment
When finished working:(deactivate)

```deactivate```

From the project directory i.e. folder where the files are: (Reactivating)

```source .venv/bin/activate```

## Usage

1. Edit the **Configuration** cell with your desired settings, including the file path.
3. Run all cells (`Cell → Run All`).  
4. Review the outputs in the specified directories.
