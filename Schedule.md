# Schedule Harvard CS109 2015
Notes
- homework CS109 2015 was not released publicly. As fas as I did the homework in 2020, it is based on CS109 2014. The HW links in column `Due (Thursdays)` point to my solution (the homework directory also contains the given 2014 solutions).
- weeknumber links provide access to [Class material](#Class-material)


Week | Tuesday | Thursday | Sections | Released (Thursdays) | Due (Thursdays)
-------------------------|-------------------|-----------|---------------|------------------|------------
                         | **Act 1: Prediction and elections** ||||
[1](#Week-1)                   | no class          |       Introduction. What is data science? Process. Why is it important? Who are we? Course overview. - HP/VK/JB   |   Friday Lab: Git and installing python. Basic Python.          | HW0              |    
[2](#Week-2)                   | Data Collection. Web Scraping. Regular Expressions. Data Reshaping. Data Cleanup. Pandas. - VK |Exploratory Data Analysis. Effective Visualizations. - HP   |   Git and installing python. Basic Python.| HW1              |[HW0](Labs/2015lab1/hw0.ipynb)
[3](#Week-3) | Introduction to Databases. SQL. More Pandas. - RD | Probability review. Statistical models. Parametric and nonparametric methods. Bootstrap. - JB | Scraping and Pandas in 1D | |
[4](#Week-4) | Effective Communication. Writing Reports. - HP / JB |	Linear regression. Logistic regression. - JB |	Pandas in 2D and stats	|HW2	|[HW1](Homework/HW1.ipynb)
[5](#Week-5) | LASSO. Regularization. Bias and sampling. Bias-variance tradeoff. Overfitting. - JB |	Classification. kNN. Cross Validation. Dimensionality Reduction. PCA. MDS. - HP |	SciKit Learn, Regression, Logistic Regression| |
|**Act 2: Recommendation & Business Analytics**||||
[6](#Week-6) | Support Vector Machines (SVM). Performance Evaluation (PR, ROC) - VK	| Decision Trees. Random Forests. - VK |	Bias/Variance in regression and classification. Regularization and Feature Selection.|	HW3	|[HW2](Homework/HW2.ipynb)
[7](#Week-7) | Ensemble Methods. Bagging. Boosting. - JB|Machine Learning Best Practices. Similarities, recommendations - VK|Fully solved example using a telecom churn dataset||
[8](#Week-8) | Amazon EC2, AWS Datastore, MapReduce - VK|Spark. - RD|Ensemble Methods|HW4|[HW3](Homework/HW3.ipynb)
|**Act 3: Bayes, CLustering & Text Analysis**||||
[9](#Week-9) | Bayesian thinking and methods. Prior distributions, likelihood. Naive Bayes. - JB|Advanced Bayesian Thinking. - JB|EC2 and Spark||
[10](#Week-10) | Text Analysis. LDA. Topic Modeling. - JB|Interactive Visualizations. Tableau. - HP|Bayesian Thinking|HW5|HW4
[11](#Week-11) | Clustering. k-means. Mean Shift. Hierarchical Clustering. - VK|Effective Presentations. - HP|Text Analysis: From Naive Bayes to LDA	||ROJECT PROPOSALS DUE
[12](#Week-12) | Experimental Design. A/B testing.Tirthankar Dasgupta|Deep Learning. - VK|Wrapup: Completely worked example: Chicago Inspections Dataset||HW5, PROJECT REVIEW WEEK
[13](#Week-13)|No class Thanksgiving||		No class Thanksgiving||
14|TBA|Wrap-up & Outlook|||
15|No class Reading Period|	No class Exam Period|	No class Exam Period||		Project
16|Final Project Presentations|	No class Exam Period|	No class Exam Period||




# Class material
Labs and Lectures are hyperlinked, not the videos as they are not in the repository due to their size. However [instructions for download](Videos/Video%20download.ipynb) these videos under Windows are provided.

### Week 1
Lecture 1: **Course overview**
-	[Slides](Lectures/01-Introduction.pdf)
-	Video

### Week 2
Lab 1: **Pandas, Python and GitHub**
-	[Repository](Labs/2015lab1)
-	Video

Lecture 2:
-	[Repository](Lectures/02-DataScrapingQuizzes.ipynb)
-	Video

Lecture 3: Exploratory Data Analysis
-	[Slides](Lectures/03-EDA.pdf)
-	Video

### Week 3
Lab 2: **Scraping, Pandas, Python and viz**
-	[Repository](Labs/2015lab2)
-	Video

Lecture 4: Pandas, SQL and the Grammar of Data
-	[Repository](Lectures/Lecture4/PandasAndSQL.ipynb)
-	[Slides](Lectures/04-PandasSQL.pdf)
-	Video

Lecture 5: Statistical Models
-	[slides](Lectures/05-StatisticalModels.pdf)
-	Video

### Week 4
Lab 3: **Probability, Distributions and Frequentist Statistics**
-	[Repository](Labs/2015lab3)
-	Video

Lecture 6: Story Telling and Effective Communication
-	[Slides](Lectures/06-StoryTelling.pdf)
-	Video

Lecture 7: Bias and Regression
-	[Slides](Lectures/07-BiasAndRegression.pdf)
-	Video

### Week 5
Lab 4: **Regression, Logistic Regression: in sklearn and statsmodels**
-	[Repository](Labs/2015lab4)
-	Video

Lecture 8: More Regression
-	[Slides](Lectures/08-RegressionContinued.pdf)
-	Video

Lecture 9: Classification. kNN. Cross Validation. Dimensionality Reduction. PCA. MDS
-	[Slides](Lectures/09-ClassificationPCA.pdf)
-	Video

### Week 6
Lab 5: **Machine Learning**
-	[Repository](Labs/2015lab5)
-	Video

Lecture 10: SVM, Evaluation
-	[Slides](Lectures/10-SVMAndEvaluation.pdf)
-	Video

Lecture 11: Decision Trees and Random Forests
-	[Slides](Lectures/11-DecisionTreesAndRandomForest.pdf)
-	Video

### Week 7
Lab 6: **Machine Learning 2**
-	[Repository](Labs/2015lab6)
-	Video

Lecture 12: Ensemble Methods.
-	[Slides](Lectures/12-Ensemble%20Learning%20and%20Random%20Forests.pdf)
-	Video

Lecture 13: Best Practices
-	[Slides](Lectures/13-BestPractices_Recommendations.pdf)
-	Video

### Week 8 
Lab 7: **Ensembles**
-	[Repository](Labs/2015lab7)
-	Video

Lecture 14: Best Practices, Recommendations and MapReduce
-	[Slides](Lectures/14-Recommendations_MapReduce.pdf)
-	Video

Lecture 15: MapReduce Combiners and Spark
-	[Slides for MapReduce](Lectures/15a-MapReduce_Combiner.pdf)
-	[Slides](Lectures/15b-Spark.pdf) and [Notebook](Lectures/15b-Spark.ipynb) for Spark
-	Video

### Week 9
Lab 8: **Vagrant and VirtualBox, AWS and Spark**
-	[Repository](Labs/2015lab8)
-	Video

Lecture 16: Bayes Theorem and Bayesian Methods
-	[Slides](Lectures/16-BayesianMethods.pdf)
-	Video

Lecture 17: Bayesian Methods Continued
-	[Slides](Lectures/17BayesianMethodsContinued.pdf)
-	Video

### Week 10
Lab 9: **Bayes**
-	[Repository](Labs/2015lab9)
-	Video

Lecture 18: Bayesian Methods Continued, Text Data
-	[Slides](Lectures/18TextData.pdf)
-	Video

Lecture BONUS: Interactive Visualization
-	Video

### Week 11
Lab 10: **Text and Clustering**
-	[Repository](Labs/2015lab10)
-	Video

Lecture 19: Clustering
-	[Slides](Lectures/19-Clustering.pdf)
-	Video

Lecture 20: Effective Presentations
-	[Slides](Lectures/20-Presentations.pdf)
-	Video

### Week 12
Lab 11: **Projects and an example** (Harvard indicated this lab, probably erroneously, as Lab 10)
-	[Repository](Labs/2015lab11)
-	Video

Lecture 21: Experimental Design
-	[Slides](Lectures/22ExperimentalDesign.pdf)
-	Video

Lecture 22: Deep Networks
-	[Slides](Lectures/23-DeepLearning.pdf)
-	Video

### Week 13
Lecture 23: Guest Lecture: Building Data Science
-	Video

Lecture 24: Wrapup and where to go from here
-	[Slides](Lectures/23-WrapUp.pdf)
-	Video


```python

```
