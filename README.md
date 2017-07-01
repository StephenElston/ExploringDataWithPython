# Exploration and Visualization of Data With Python

## Tutorial presented at PyData Seattle, July 2016  

This Jupyter notebook introduces you to some basic principles data exploration and visualization using the Python language. The lessons contained in the notebook, revolve around exploration of the characteristics of a number of automobiles. The ultimate goal is to build a model for predicting the price of a car from its characteristics. The goal is to understand the relationships in these data using visualization methods. 

## About this Jupyter Notebook
The Jupyter notebook contains material to help you learn how to explore data visually. This notebook and the data set can be downloaded from GitHub:

**https://github.com/StephenElston/ExploringDataWithPython**  

This notebook was constructed using the Anaconda 3.5 Python distribution. If you are not running version Anaconda 3.5 or higher, we suggest you update your Anaconda distribution now.  You can download the Python 3 Anaconda distribution for your operating system from the [Continum Analytics web site](https://www.continuum.i

``conda install seaborn``

or 

``pip install seaborn``  



## About the author

These lessons have been prepared by **Steve Elston** who is co-founder and principle consultant Quantia Analytics, LLC. Steve is a long time data geek and analytical software pioneer, having lead R&D at the SPlus companies and co-founding FinAnalytica, among other positions. He assists clients with staff training and analytics problems in a number of areas. A summary of his activities include:  

- Instructor, University of Washington and Harvard University data science programs
- O'Reilly author and creator of four edX data science courses
- Decades of experience in predictive analytics and machine learning 
- Microsoft Data Most Valued Professional, MVP
- Experience in several industries: payment, telecom, capital markets, logistics, energy
- PhD, MS in Geophysics from Princeton University

## Why visualization?

Visualization is an essential method in any data scientist’s toolbox. Visualization is a key first step in the exploration of most data sets. As a general rule, you should never start creating models untilo/downloads)

To run this notebook you need the Seaborn graphics packages. If you have not done so, you will need to install Seaborn as it is not in the Anaconda distribution as of now. From a command prompt on your computer type the following command. If no errors occur, you will have installed Seaborn.

``pip install seaborn``

or you have examined the data and understand the relationships. Otherwise, you risk wasting your time creating models blindly. Visualization is also a powerful tool for presentation of results and for determining sources of problems with analytics. 

The concepts of exploring a data set visually were pioneered by John Tukey in the 1960s and 1970s. Tukey consolidated his many ideas on data exploration into a book in the late 1970s, ***John Tukey, Exploratory Data Analysis, 1977, Addison-Westley***.

Bill Cleveland documented his seminal work in visualization of complex data sets in his book, ***William S. Cleveland, Visualizing Data, 1993, Hobart Press***.

The key concept of exploratory data analysis (EDA) or visual exploration of data is to understand the relationships in the data set. Specifically using visualization when you approach a new data set you can:

- Explore complex data sets, using visualization to develop understanding of the inherent relationships.
- Use different chart types to create multiple views of data to highlight different aspects of the inherent relationships.
- Use plot aesthetics to project multiple dimensions. 
- Apply conditioning or faceting methods to project multiple dimensions



These lessons are divided into three parts. In each part you will learn how to use the visualization tools available in Python.

- **Overview of plot types** is a review of creating basic plot types used to construct visualizations.
- **Using Aesthetics** is an overview of how to project additional plot dimensions using plot aesthetics.
- **Facetted plotting** also know as conditioned plotting or lattice plotting introduces a powerful method for visualizing higher dimensional data. 

In these exercises, you will use both Pandas plotting and the Seaborn package. We assume you have at least a bit of experience using Pandas and Jupyter notebooks.  


## Resources

In this tutorial we will work with two powerful Python packages, Pandas and Seaborn. Both packages have extensive online documentation. There is an extensive tutorial on [**Visualizaton with Pandas**](http://pandas.pydata.org/pandas-docs/version/0.18.0/visualization.html).  The [**Seaborn tutorial**](https://stanford.edu/~mwaskom/software/seaborn/tutorial.html) contains many examples of data visualization. The matplotlib web site has addition [**resources for learning plotting with Python tools**](http://matplotlib.org/resources/index.html).

