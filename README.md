# Data-Exploration--Data-Clustering-
# DATA EXPLORATION

The aim of this data exploration is to explain and to illustrate the different steps needed when approaching collected data with the purpose to analyze it. The first phase is to explore the data and to prepare it for the analysis. It is also referred to as 'Understanding the Data'. While there are sophisticated tools available for the analytical part together with the visualization of the data, we want to stress the importance of starting out with a systematic way of statistically analyzing the data in order to find out about important characteristics. This knowledge gained about the data makes the analytical work with high-level tools much more efficient. 

We are using a dataset about the life expectancy in different countries based on data collected by the World Health Organization (WHO) as presented in a Kaggle-project, see https://www.kaggle.com/kumarajarshi/life-expectancy-who



<br />
<br />

---


Appreciation and thanks for inspirations are due to the following people and their contributions:

- Philip Bowman for his excellent Kaggle-notbook on 'Life Expectancy: Exploratory Data Analysis', see: https://www.kaggle.com/kumarajarshi/life-expectancy-who
- Harshini Gadige for her Kaggle-notebook on 'Life Expectancy Cleaning,EDA,Feature Engineering', see: https://www.kaggle.com/harshini564/life-expectancy-cleaning-eda-feature-engineering
- Magnus Vilhelm Persson & Luiz Felipe Martins, 'Mastering Python Data Analysis', Birmingham, UK, Packt Publishing, 2016.
student project by Ladan Farbiz ladanfarbiz@yahoo.com for Malmo University

#Data Clustering

Exploring data is mainly about developing an understanding for the kind of questions that the data can answer. In order to find out about what kind of conclusions one can draw from the data one needs to identify statistical patterns in the data. There are no fast given rules of how to best proceed and success is mainly based on building up an intuition for the different techniques that are suitable in each case from working on own datasets.

We continue to use the Life expectancy data set in this tutorial as prepared under the previous tutorial. The obvious question one can ask regarding the life expectancy is regarding the different factors that relate or possibly result in higher life expectancy or in a wide variation of life expectancy among different countries and regions in the world. 
Another possibility offered by the data set is to focus on the question regarding the difference between 'developing' and 'developed' countries.

The aim of this project is to examplify the methods regarding the clustering of data. As teh name already indicares, clustering of data is mainly used to visualize clusters, e.g. groups within the data that share similar properties. This clustering is entirely based on statistics and does not need to have any meaning in the real world. But it can highlight common properties inherent in the data that otherwise is not visible.

The content in this tutorial is organized as follows:

- 1. Importing the resulting data frame variables from previous tutorial

- 2. Clustering
  - 2.1 Identifying 2 Clusters
    - 2.1.1 K-means method
    - 2.1.2 Comparison between clustering and classification into developing and developed countries
  - 2.2 Identifying the optimal number of clusters
    - 2.2.1 Identifying 3 clusters
    - 2.2.2 Comparing clustering with all of the variables
    - 2.2.3 Plotting the scatterplots of all of the significant single values
- 3 Dimensionality reduction 
  - 3.1 Scatterplot of reduced dimensions
  - 3.2 Identifying countries



Appreciation and thanks for inspirations are due to the following people and their contributions:
- Philip Bowman for his excellent Kaggle-notbook on 'Life Expectancy: Exploratory Data Analysis', see: https://www.kaggle.com/kumarajarshi/life-expectancy-who
- Harshini Gadige for her Kaggle-notebook on 'Life Expectancy Cleaning,EDA,Feature Engineering', see: https://www.kaggle.com/harshini564/life-expectancy-cleaning-eda-feature-engineering
- Magnus Vilhelm Persson & Luiz Felipe Martins, 'Mastering Python Data Analysis', Birmingham, UK, Packt Publishing, 2016.

### done by Ladan Farbiz ladanfarbiz@yahoo.com
