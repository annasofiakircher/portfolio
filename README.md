# Anna Sofia Kircher
www.linkedin.com/in/annasofiakircher

In this github repository you can find some examples of my work which show some of my skills.

# Projects
* Quality Machine
* Unbalanced Random Forest
* Energy Demand Model
* SAT Scores in NYC

# Quality Machine
The R Notebook QualityMachine is based on the results in 'Quality Minus Junk' by Asness, Frazzini and Pedersen. Their methodology includes long/short portfolios and in-sample estimated predictors of a company's future default probability. Furthermore, ad hoc choices are made regarding weighting of quality measures and stocks in the actual portfolio. These choices make it virtually impossible to replicate the portfolio in reality. All these objections are handled by creating a factor that is a long-only portfolio assembled by a Random Forest. This machine learning mechanism is fed with balance sheet and stock return data of companies that existed in the last 5 years. In-sample estimated series are not included. The random forest learns from this data and applies the resulting decision rules to current book data. This approach gives similar results as the original paper, so it appears that the existence of the quality premium is robust to the author's methodology. is a short version of my master thesis, where I used sampling methods to overcome the imbalance problem using Random Forests for a multiple class classification.

The Word document called 'QualityMachine.docx' is a short version of the notebook.

# Random Forest
The 'Notebook_RandomForest' is a short version of my master thesis, where I used sampling methods to overcome the imbalance problem using Random Forests for a multiple class classification.

The Word document called 'unbalanced_random_forest.docx' is a brief overview of my thesis.

Both are based on the so-called comecs data which can be found as a Rda file: comecs_data.Rda

## What is analyzed?
The spectral measurements of ten meteorites are investigated to determine whether or not the spectral composition of different meteorites allows a distinctive classification of the meteorites.

## Motivation
After a colleague of mine did some kNN clustering on the spectral compositions of meteorites, we were interested how Random Forest would perform. Especially regarding the variable importance, which was a great feature for this analysis.

## Data and Installation
My analysis is based on the so-called comecs data set which can be found in this repository. The code junks in the notebook are small samples of what I did in my thesis. So you can run the code without overloading your computer.

# Energy Demand Model
Time series regarding electricity consumption, prices and GDP are used to try to fit a demand model to investigate the electricty consumption for Finland and Norway.
Four different models are fitted to the data and compared such that one final model could be chosen.

## Data
The timeseries start in 1978 and end in 2008. All data sets can be downloaded form this repository.

# SAT Scores - NYC
Based on demografic and other information about high schools in New York City, I've done some analysis on SAT scores. In the notebook 'SATscores_NYC' every step of analysis and conclusions can be retraced. 

A short version can be found in the Word document called 'SATscores_NYC.docx'.

## Motivation
I recently moved to New York and since I'm not really familiar with the American education system I found this analysis very helpful as a starting point. 

## What is investigated?
During the analysis followin questions are investigated:
* What variables have the biggest influence (in terms of correlation) on the total SAT scores?
* Is demographic information important?
* Are the SAT fair? Concerning the allegations about the SAT being unfair to certain racial groups or biased by gender?

## Data
All data sets can be found in this repository.

# R & Python
As my preferred programming language I used R for almost all projects. The energy demand model analysis were analyzed and built in Python.
