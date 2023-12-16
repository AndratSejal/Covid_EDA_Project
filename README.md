# Covid_EDA_Project

How to perform EDA?

1. Summary Statistics

These are measurements to describe data. We can use df.describe() function to get various summary statistics. However, this process excludes NaN values and categorical values. To include description for categorical data we need to use df.describe(include= "all") .

2. Visualise

Different visualisation techniques such can histogram, scatter plots, box plot, distribution plots, maps, etc can be used to perform EDA.

In this article, we will do EDA using the COVID-19 dataset. We will use different commonly used EDA techniques to discover patterns in the COVID-19 dataset. The complete code can be found on my github.

Datasets

We will be working with the publicly available datase .The data repository consists of different datasets related to covid-19. I merged and concat the relevant data. You can find modified dataset on my github.

This dataset total conatins 12 features which is described as below:
1.Country: Contains 230 differnt countries names

2.Total Cases: Total covid cases occured in (Millions)

3.Total Deaths: Total death rate due to covid in (Millions)

4.New Deaths: New Death Rate

5.Total Recovered: Total recovered cases in (Million)

6.Active Cases: Total Active cases in (Million)

7.Serious Cases: Total Serious cases in (Thousands)

8.Total Cases/1M pop: Total Covid cases occured per 1Million Population

9.Deaths/1M pop: Total Death rate per 1Million Population

10.Total Tests: Total Test

11.Test/1M pop: Total Test of Covid cases done per 1Million Population

12.Population: Total no. of Population
