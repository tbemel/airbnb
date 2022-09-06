# Air BnB Paris and Dublin - What Key BnB Features Most Influence Price and Ratings? 
This repository contains a Jupyter Notebook, leveraging Data Science techniques to analysethe Seatle and Bostong Air BNB listing. It focuses on understanding the key features that mostly influence the BNB ratings and price.<br> It follows the CRISP-DM methodology: business understanding <=> data understanding <=> data preparation <=> modeling <=>  evaluation (deployment would be left for systematic usage).

See my blog on Medium for the key findings: https://medium.com/@tbemel/plan-to-stay-in-a-bnb-paris-or-dublin-a04daecdf371

The Jupyter Notebook covers the key CRISP-DM process with practical python code snypets to load data, analyse the key features, see their correlations, leverage Matplotlib and SeaBorn modules to provide powerful visual insights, prepare the data, taking care of the missing value, removing noisy columns, reformating the price and rating columns to be read as numeric, leverage NLP techniques to augment the data set with BNB description word count vectors, prepare the prediction models with the data splitting into test/train sets, run the models and analyse the results. It especially focuses on visualizing the key factors influencing the BNB price and rating.

## Table of Content
1.	Installations
2.	Project Motivation
3.	File Descriptions
4.	How to Interact with your project
5.	Licensing, Authors, Acknowledgements, etc.

## 1.	Installations
The following components are needed to run this Jupyter Notebook:
- Python version 3.9 + with Jupyter Notebook installed
- Key python modules needed, if possible install the latest release: numpy, pandas, sklearn, NLTK, matplotlib, seaborn, plotly
- After installing NLTK, ensure you run the python command nltk.download() to download all NLTK data packages. 
- The BnB data sets for numerous international cities can be found here http://insideairbnb.com/get-the-data/ 
I downloaded the listings from Paris 06 June 2022 & Dublin of 08 June, 2022

## 2.	Project Motivation
As part of my Udacity Data Science Nano Degree, I wanted to leverage, ground and share my key learnings with a practical data science use case.  
I also wanted to experiment new ways to analyzing and visualizing data. I particularly enjoyed the geo location visuals and deep diving on the boxplots. 

## 3.	File Descriptions
- README.MD : this file
- Data Science-AirBNB-Paris-Dublin.ipynb : the Jupyter Notebook with the python code. - 

## 4.	How to Interact with this project?
Feel free to add comments and fork the code. Would love to hear from your own feedback and suggestions. 

## 5.	Licensing, Authors, Acknowledgements
This project is subject to the GNU license GPL v3 https://www.gnu.org/licenses/gpl-3.0.en.html
Author: Thierry Bemelmans
Acknowledgements: Udacity Data Science Nano program for the methodology and certain data modelisation techniques, python open source modules contributors and bloggers.

