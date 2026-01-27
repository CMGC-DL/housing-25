# housing-25
Central Maine Growth Council (CMGC) has created the following analytical tool to create visualizations and conduct seasonal adjustments to housing data obtained from Realtor.com. This repo contians the .ipynb that takes in a valid dataset and provides the outputs based on the variables configured. 

“This project is provided as-is for research, educational, advocacy, and commercial use. The authors and affiliated nonprofit assume no responsibility for outcomes derived from its use.”

"# Housing Data Analysis Notebook\n",
    "## Created by: Central Maine Growth Council\n",
    "## Data Source: [Realtor.com](https://www.realtor.com/research/data/) Research Data\n",
    "\n",
    "This notebook analyzes housing market metrics for a specified ZIP code, comparing against state and national trends. It produces:\n",
    "- Seasonal adjustment analysis using Prophet\n",
    "- Geographic comparison plots (ZIP vs State vs National)\n",
    "- Yearly summary tables\n",
    "\n",
    "### Requirements\n",
    "1. This is a python3 based jupyter-notebook and requires that python is install along with jupyter-lab or note book\n",
    "   - see this link to understand how to install these\n",
    "2. The following python libraries are needed\n",
    "   - pandas\n",
    "   - numpy\n",
    "   - math\n",
    "   - os\n",
    "   - warnings\n",
    "   - prophet\n",
    "   - plotly\n",
    "   - kaleido\n",
    "3. You must have google chrome installed\n",
    "\n",
    "### Usage\n",
    "1. Edit the **Configuration** cell below with your settings\n",
    "2. Run all cells (Cell → Run All)\n",
    "3. Check the outputs in the specified directories"
