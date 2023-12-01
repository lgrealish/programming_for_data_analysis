 # Programming for Data Analysis Assignment 1


This repository contains my submission for the Programming for Data Analysis Module 2023 module at ATU as part of the Higher Diploma in Computing and Data Analytics.

## Problem statement:

For this project you must create a data set by simulating a real-world phenomenon of your choosing. You may pick any phenomenon you wish – you might pick one that is of interest to you in your personal or professional life. Then, rather than collect data related to the phenomenon, you should model and synthesise such data using Python. We suggest you use the numpy.random package for this purpose.

Specifically, in this project you should:

- Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four different variables.
- Investigate the types of variables involved, their likely distributions, and their relationships with each other.
- Synthesise/simulate a data set as closely matching their properties as possible.
- Detail your research and implement the simulation in a Jupyter notebook – the data set itself can simply be displayed in an output cell within the notebook.

Note that this project is about simulation – you must synthesise a data set. Some students may already have some real-world data sets in their own files. It is okay to base your synthesised data set on these should you wish (please reference it if you do), but the main task in this project is to create a synthesised data set. 


## Dataset chosen

I have chosen to base my synthesised dataset on an existing dataset, the Titanic dataset.

On April 15, 1912, the largest passenger liner ever made collided with an iceberg during her maiden voyage. When the Titanic sank it killed 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships. One of the reasons that the shipwreck resulted in such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others.

The titanic.csv file contains data for 891 of the real Titanic passengers. Each row represents one person. The columns describe different attributes about the person including;

- whether they survived 
- passenger class
- sex
- age
- port at which they embarked
- siblings/spouse onboard
- fare paid.


# Dependencies
* [NumPy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org/)
* [Matplotlib](http://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/index.html#)




# References/Research

https://towardsdatascience.com/generating-expanding-your-datasets-with-synthetic-data-4e27716be218

https://www.kdnuggets.com/2022/03/generate-tabular-synthetic-dataset.html

https://data.world/nrippner/titanic-disaster-dataset

https://ema.drwhy.ai/dataSetsIntro.html

https://stackoverflow.com/questions/73094559/how-to-fill-a-pandas-dataframe-column-with-one-of-two-list-values

https://rpubs.com/kar_ng/827540

https://numpy.org/doc/stable/reference/random/legacy.html#distributions

https://stackoverflow.com/questions/71948991/how-to-create-synthetic-data-based-on-dataset-with-mixed-data-types-for-classifi

https://gist.github.com/mwaskom/de44147ed2974457ad6372750bbe5751

https://makeschool.org/mediabook/oa/tutorials/titanic-dataset-tutorial-an-intro-to-data-analysis-and-statistics-n40/pdfs-and-cdfs/

https://dev.to/pavanbelagatti/data-analysis-of-the-titanic-with-python-koj

https://numpy.org/doc/stable/reference/random/generated/numpy.random.normal.html

https://www.digitalocean.com/community/tutorials/pandas-dropna-drop-null-na-values-from-dataframe

https://realpython.com/numpy-random-normal/#specify-the-mean-and-standard-deviation

https://numpy.org/doc/stable/reference/random/generated/numpy.random.lognormal.html



