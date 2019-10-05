# Multilabel Text Classification
## Predicting Tags for Stack Overflow

The question tests the skills to manipulate large dataset from the csv file. The task is to predict the tags (a.k.a. keywords, topics, summaries) given only the question text and its title. The dataset contains content containing a mix of both technical and non-technical questions. The data file `Train.csv` can be downloaded from [
Facebook Recruiting III - Keyword Extraction](https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/data).

## Prerequisites: Python

Python is a requirement (Python 3.3 or greater) to install the Jupyter Notebook.

It is recommended to use the Anaconda distribution to install Python and Jupyter Notebook. 

Install the latest version of the Anaconda 3 distribution which will include an IDE like Spyder. This is the link to download the appropriate version for different operating systems: [Anaconda Distribution](https://www.anaconda.com/download/)

## Installation

After Anaconda is installed, Jupyter Notebook will be available to use. 

To run Jupyter Notebook from Terminal, open Anaconda Prompt and run: jupyter notebook (normally jupyter-notebook.exe can be found in .../anaconda3/scripts/ directory).

From Jupyter Notebook: Open the file `Predicting Tags Based on Title and Text` and run it.

## Packages Used

Packages can be installed by running the following command in the terminal: 

    pip install -r pip_requirements.txt
    
* `numpy==1.16.1`
* `pandas==0.23.0`
* `seaborn==0.8.1`
* `matplotlib==2.2.2`
* `re==2.2.1`
* `bs4==4.6.0`
* `nltk==3.3`
* `scikit-learn==0.19.1`
* `scikit-multilearn==0.2.0`

## Notes

* This program was built using Windows 10.
* Python 3.6.5 was used.
* Tested successfully on Windows 10.