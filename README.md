# BigMacIndex

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Beyond all the standard packages in the Anaconda distribution of Python the following packes should be installed to run the code:
 - pycountry
 - requests
 
The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interested in the prices Big Macs have around the world, and how this translates into the Big Mac Index.
Besides, I was also curious how the price of a Big Mac corresponds with local a local price indicator like the CPI.

Therefore I tried to answer the following research questions:

1. Do Big Mac prices serve as a proper exchange rate indicator?
2. Which countries have, based on the Big Mac Index, more purchasing power? (compared to the US)
3. Which countries have, based on the Big Mac Index, less purchasing power? (compared to the US)
4. Does local BigMac price development follow a similar trend as a country's CPI?

## File Descriptions <a name="files"></a>

There are 2 notebooks available here to showcase work related to be above mentioned research questions:
- BigMacPrices - Clean --> Jupyter notebook that cleans and combines the Big Mac price dataset + joins it to the CPI data
- BigMacPrices - Analyses --> Notebook that analyses the cleaned dataset and tries to answer the research questions

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit must be given to the kaggle user "Vittorio Giatti" for making this datasat available to the public via the following [link](https://www.kaggle.com/datasets/vittoriogiatti/bigmacprice?resource=download)

The data regarding CPI have been downloaded from the OECD via the following [link](https://data.oecd.org/price/inflation-cpi.htm)

