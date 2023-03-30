# COVID-19 Data Analysis
This repository contains an analysis of the COVID-19 pandemic using data on confirmed cases throughout the world. The main focus is to compare the trends in China to the rest of the world, with additional annotations and visualizations to provide more insights.
## Contents
1. **From epidemic to pandemic:** An overview of the progression of the COVID-19 outbreak from an epidemic in China to a global pandemic.
2. **Confirmed cases throughout the world:** Visualization of the cumulative confirmed cases of COVID-19 worldwide over time.
3. **China compared to the rest of the world:** A comparison of the trends in confirmed cases between China and the rest of the world.
4. **Let's annotate!:** Adding important events as annotations to the plot to provide context and help understand the progression of the pandemic.
5. **Adding a trend line to China:** Fitting a linear regression trend line to the confirmed cases data for China.
6. **And the rest of the world?:** Fitting a linear regression trend line to the confirmed cases data for the rest of the world.
7. **Adding a logarithmic scale:** Transforming the y-axis to a logarithmic scale to better visualize the exponential growth of cases.
8. **Which countries outside of China have been hit hardest?:** Identifying the countries with the highest number of confirmed cases outside of China as of mid-March 2020.
9. Plotting hardest hit countries as of Mid-March 2020: Visualizing the trends in confirmed cases for the hardest-hit countries outside of China as of mid-March 2020.
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with R kernel support. Make sure to install the required packages such as `tidyverse`. You can do this by running the following commands in a code cell within the notebook:
``` r
install.packages("tidyverse")
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the R kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Install the R kernel for Jupyter Notebook by running the following commands in your R console:
``` r 
install.packages("IRkernel")
IRkernel::installspec()
```
After completing the installation, launch Jupyter Notebook, navigate to the folder containing the notebook file, and open it to begin running the analyses.

