# Machine Learning Engineer Nanodegree
# Capstone Project
## Project: Classifying Households

This project uses supervised learning techniques for classification of households into two groups for payments via cash transfers

## Install

This project requires **Python 3.6.* ** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [XGBoost](https://xgboost.readthedocs.io/en/latest/)
- [Jupyter notebook / iPython Notebook](http://ipython.org/notebook.html)

## Data

The dataset consists of 100,000, with 18 features. The dataset can be downloaded from [this link](https://github.com/dakn2005/MLNDProject_CT/blob/master/mlnd-ds-2.csv) on github

**Features**
- `Gender`: Male, Female
- `Age`: continuous.
- `Attended_school`: Currently attending, Never, Yes but not now, SKIP
- `Work_last_7days` (had work at time of registration ?): SKIP, Worked for pay, On leave, Sick leave, Worked on own/family, business, Herding-Worked on own/family agri. holding, Seeking work, Doing nothing, Retired, Homemaker, Full-time, student, In capacitated, Other
- `Chronic_illness`: 0 - false, 1- true, 2-skip
- `Disabled`: 0- false, 1- true
- `YearsChronicallyIll`: continuous
- `WealthGroup`: Better Off, Middle, Poor, Very Poor
- `Resident_Provider`: SKIP, All live here all of the time, Some live here while others migrate, All migrate together-fully mobile, Inside this household, Outside household but inside compound-settlement, Outside this compound-settlement
- `Polygamous`: discrete
- `Children_Under_15`: discrete
- `kids_under_15_in_settlement`: discrete
- `wives_in_settlement`: discrete
- `spouses_outside_hh`: discrete
- `Toilet`: Flush toilet, VIP latrine, Uncovered pit latrine, Covered pit latrine, Bucket/pan, Bush-None, Other
- `Drinking_water`: Piped water inside dwelling, Piped water into plot/yard, Public tap, Tube well/borehole with pump, Protected dug well, Protected spring, Rainwater collection, Unprotected dug well/springs, River, Lake, ponds or similar, Water truck/vendor, Bottled water, Other
- `Land_Ha`: discrete

**Target Variable**
- `HHGroup`: categorical (True, False)
