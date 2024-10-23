# IBM Article Recommendations

In this project, I analyze the articles that users have interacted with on the IBM Watson Studio platform, and then make recommendations of new articles to them. I completed this project as a part of the Udacity nanocourse in Datascience.


### Table of Contents

1. [Requisites](#requisites)
2. [Data](#data)
3. [Project Motivation](#motivation)
4. [File Descriptions](#files)
5. [Licensing, Authors, and Acknowledgements](#licensing)


##  Requisites<a name="requisites"></a>
This project requires Python 3.x and the following Python libraries installed:
- [Pandas](http://pandas.pydata.org)
- [Numpy](https://numpy.org)
- [Matplotlib](https://matplotlib.org)


## Data<a name="data"></a>
- user-item-interactions.csv: this file contains the various user-article interactions.
- articles_community.csv: this file contains the description of the articles.  

## Project Motivation<a name="motivation"></a>

For this project, I analyzed the articles that users already interacted with on the IBM platform. After performing this analysis, I tried different techniques to recommend new articles to these users. These recommendations included:

1. ***Rank-based recommendations*** : This approach involves recommending the most popoular articles to the users. These articles serve as good recommendations to new users.
2. ***User-based recommendations*** : This approach involves recommending articles to users based on other users who showed same preferences as them (i.e. they viewed the same articles previously).
3. ***Content-based recommendations*** : This approach involves recommending articles to users based solely on the previous articles they interacted with. 
4. ***Matrix factorization technique*** : This approach uses matrix decomposition on the user-item interactions and made predictions based on the results. 

## File Descriptions <a name="files"></a>

There is a Juptyer notebooks in this repository to showcase the work related to the above questions.  The notebook is exploratory in searching through the data pertaining to the questions showcased by the notebook title. To assist with the thought process of creating the notebook, markdown cells were used.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

I thank [Udacity](https://www.udacity.com) for this insightful project. The data was generously provided by [IBM](https://dataplatform.cloud.ibm.com/). 

This project is licensed under the terms of the MIT license.
