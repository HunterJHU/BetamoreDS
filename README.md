# Betamore: Applications of Data Science

***INSTRUCTOR***

Hunter Jackson
*	Cofounder of [Proscia](https://www.proscia.com)
*	Ph.D. Candidate in Mathematics at [Hopkins](https://www.math.jhu.edu)

***COURSE OUTLINE***

Each class will be an engaging, interactive session where we build tools together to make predictions about our data. The classes will be focused on actually building the predictive tools; however, each class will have supplementary lecture notes that describe the methodologies in further detail and extra programming tasks if anyone wants extra practice.

We held the info session on 3/16 at Spark Baltimore, if you missed it, you can find details about the course [here](https://github.com/HunterUSF/BetamoreDS/blob/master/lecturenotes/DS_infosesh.pdf)

Class 1: Intro DS + Python Basics + Intro ML:
=============================================

*	Class intro: [slides](https://github.com/HunterUSF/BetamoreDS/blob/master/lecturenotes/DS_courseintro.pdf)
*	Class 1 Notes: [slides](https://github.com/HunterUSF/BetamoreDS/blob/master/lecturenotes/DS_lecture1.pdf)
*	A lil Python refresher: [code](https://github.com/HunterUSF/BetamoreDS/blob/master/code/pythonbasics.py)
*	A lil Numpy refresher: [code](https://github.com/HunterUSF/BetamoreDS/blob/master/code/numpybasics.py)
*	First shot at working with data: [code](https://github.com/HunterUSF/BetamoreDS/blob/master/code/iris_work.py)
*	Build our own knn: [code](https://github.com/HunterUSF/BetamoreDS/blob/master/code/knn.py)
*	In-depth machine learning (especially section 2.1): [here](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Sixth%20Printing.pdf)
*	Excellent article on the [Bias-variance tradeoff](http://scott.fortmann-roe.com/docs/BiasVariance.html) and Andrew Ng's [course](http://cs229.stanford.edu/materials.html) on Machine learning taught at Stanford
*	The UCI ML [repo](http://archive.ics.uci.edu/ml/) containing data sets for practice 
*	Conditional probability [explained](http://setosa.io/ev/conditional-probability/) visually. Check it our and play around -- it will help a ton for the next class.


Class 2: Machine Learning 101 + Model Evaluation:
=================================================

*	Class 2 Notes: [slides](https://github.com/HunterUSF/BetamoreDS/blob/master/lecturenotes/DS_Lecture2.pdf)
*	Sci-kit learn docs: [user guide](http://scikit-learn.org/stable/modules/neighbors.html), [module reference](http://scikit-learn.org/stable/modules/classes.html#module-sklearn.neighbors), [class documentation](http://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
*	Linear Regression [notes](https://github.com/HunterUSF/BetamoreDS/blob/master/notebooks/linear_regression.ipynb)
*	Logistic Regression [notes](https://github.com/HunterUSF/BetamoreDS/blob/master/notebooks/logistic_regression.ipynb)
*	Decision Trees [notes](https://github.com/HunterUSF/BetamoreDS/blob/master/notebooks/decision_trees.ipynb)
*	Javascript tree [layout](http://bl.ocks.org/mbostock/4339184)
*	Ensemble Learning [notes](https://github.com/HunterUSF/BetamoreDS/blob/master/notebooks/ensembling.ipynb)
*	Caltech's ML course explaining bias-variance [tradeoff](http://work.caltech.edu/library/081.html)
*	Sensitivity v. Specificity [video](https://www.youtube.com/watch?v=vtYDyGGeQyo)
*	30 second explanation of overfitting [video](https://www.quora.com/What-is-an-intuitive-explanation-of-overfitting/answer/Jessica-Su)
*	Take home [project](https://github.com/HunterUSF/BetamoreDS/blob/master/projects/titanic.md) and [solutions](https://github.com/HunterUSF/BetamoreDS/blob/master/code/titanic_solutions.py) for predicting survival on the Titanic.


Class 3: Topics in Unsupervised Learning Pt. 1:
===============================================
*	Class 3 Notes: [slides](https://github.com/HunterUSF/BetamoreDS/blob/master/lecturenotes/DS_lecture3.pdf)
*	Cluster analysis [code](https://github.com/HunterUSF/BetamoreDS/blob/master/code/clusteranalysis.py)
*	Cluster analysis [reading](http://www-users.cs.umn.edu/~kumar/dmbook/ch8.pdf)
* 	Limitations of k-means clustering [code](https://github.com/HunterUSF/BetamoreDS/blob/master/code/kmeans_limits.py)
*	Sklearn [guidance](http://scikit-learn.org/stable/modules/clustering.html) on clustering
*	Using pandora data to find user clustering with this [data](https://github.com/HunterUSF/BetamoreDS/blob/master/data/pandora.csv) and this [code](https://github.com/HunterUSF/BetamoreDS/blob/master/code/pandora.py)
*	Twitter sentiment [visualization](https://www.csc.ncsu.edu/faculty/healey/tweet_viz/tweet_app/)
* ***Stock Predictions*** [project](https://github.com/HunterUSF/BetamoreDS/blob/master/projects/ZYX_stocks.pdf) using 7 months of [data](https://github.com/HunterUSF/BetamoreDS/blob/master/data/ZYX_prices.csv) including twitter sentiment, volume, and stock price to create a predictive model to predict forward returns.
*	Eigenvalues and vectors [explained](http://setosa.io/ev/eigenvectors-and-eigenvalues/) visually. Check it out and play around -- it will help a ton for the next class.



Class 4: Topics in Unsupervised Learning Pt. 2 + Databases Pt. 1:
=================================================================
*	Class 4 Notes: [slides](https://github.com/HunterUSF/BetamoreDS/blob/master/lecturenotes/DS_lecture4.pdf)
*	Principal component analysis for Iris [code](https://github.com/HunterUSF/BetamoreDS/blob/master/code/iris_pca.py)
*	Setting up PCA [code](https://github.com/HunterUSF/BetamoreDS/blob/master/code/pca_math.py)
*	Dimensionality reduction [notebook](https://github.com/HunterUSF/BetamoreDS/blob/master/notebooks/pca.ipynb)
*	PCA visually [explained](http://setosa.io/ev/principal-component-analysis/)
*	PCA step-by-step [here](http://sebastianraschka.com/Articles/2014_pca_step_by_step.html)
*	Linear discriminant analysis [explained](http://spartanideas.msu.edu/2014/08/03/linear-discriminant-analysis-bit-by-bit/)
*	Map-reduce [code](https://github.com/HunterUSF/BetamoreDS/blob/master/code/mapreduce.py)
*	What every data scientist needs to know about [SQL](http://joshualande.com/data-science-sql/)
*	Stanford [mini-series](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about) on databases
*	Practice SQL from [browser](http://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all)
*	Queries [explained](http://www.sqlite.org/queryplanner.html)
*	Work with databases in the context of machine learning [code](https://github.com/HunterUSF/BetamoreDS/blob/master/code/db_practice.py), [solutions](https://github.com/HunterUSF/BetamoreDS/blob/master/code/db_solutions.py)




Class 5: Natural Language Processing + Databases Pt. 2:
=======================================================
*	SQL [notebook](https://github.com/HunterUSF/BetamoreDS/blob/master/notebooks/sql.ipynb)
*	NoSQL/MapReduce [notebook])(https://github.com/HunterUSF/BetamoreDS/blob/master/notebooks/nosql.ipynb)
*	Here's a [reading](https://github.com/HunterUSF/BetamoreDS/blob/master/projects/planforspam.md) by PaulGraham, cofounder of Y-combinator.


Class 6: Neural Networks + Recommendation Engines:
==================================================














