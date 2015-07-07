# Big Analytics with R
Discover Deep Insights in Big Data by Thomas W. Dinsmore and James Paul 

## Audience
This book is for R users who want to harness the power of Big Analytics to produce deep insights from Big Data.  The reader understands basic principles of statistical analysis, predictive modeling and machine learning as well as fundamentals of the R programming language, and experience using R with small datasets.  The reader wants to work with Big Data, and wants to learn the necessary tools and techniques to do so.

##Mission
Discover deep insights in Big Data with R for Big Analytics.
###Objectives and achievements
The reader will learn how to:
* Evaluate different big data problems and decide an approach to solving them using a technology stack involving R
* Set up a high-performance analytics environment for R
* Use R to push SQL operations into MPP databases and Hadoop
* Extract features from unstructured data in Hadoop and NoSQL databases
* Perform unsupervised machine learning with R, Spark and H2O
* Perform supervised machine learning with R, Spark and H2O
* Perform Deep Learning with R and H2O
* Evaluate predictive models with R
* Deploy predictive models in production applications

###General structure
1. Prepare to Work With Big Data
2. Prepare Your Data for Analysis
    * Structured data in MPP databases and Hadoop
    * Unstructured data in NoSQL databases and Hadoop
    * Streaming data
3. Discover Deep Insights
    * Unsupervised machine learning with R and H2O
    * Supervised machine learning with R and H2O
    * Deep Learning with R and H2O
4. Test and Evaluate Your Models
5. Deploy Your Predictive Models
6. Closing Chapter

##Detailed outline
###Chapter 1: Prepare to Work with Big Data – 40 pages
####Description
In this chapter, we define Big Data and survey the most popular Big Data platforms.  We cover the single biggest challenge Big Data poses for R users, and the key principles of Big Analytics that will drive the remaining chapters in the book.  We will guide the user to selecting tools to set up a Big Analytics environment for R, using freely available open source software.  
####Level
BASIC

####Topics covered
* Definition of Big Data
* Popular Big Data platforms
* Principles of Big Analytics
* Challenges in Big Data Analytics
* Technology Trends affecting Big Data Analytics
* Installation and configuration
* High-performance R distributions 

#### Key R packages
H2O, an open source Big Analytics platform 
Apache Spark, an open source Big Analytics platform
#### Skills learned
The reader will learn how to design and implement a scalable platform for predictive analytics with R.


###Chapter 2: Work with Structured Data in Databases – 30 pages
####Description
The first step in an analysis project is to gather data into a single dataset at a level of aggregation that is appropriate for the business problem.  A key principle of Big Analytics is that data movement should be minimized.  In this chapter, we cover the tools and techniques needed to perform data processing operations inside source databases from the R interface.
####Level
MEDIUM
####Topics covered

* Architectural trends in modern databases
* Using key R packages, such as RODBC and dplyr
* Push-down processing in commercial MPP databases
* HP Vertica
* IBM PureData (Netezza)
* Oracle Big Data Appliance
* Pivotal Greenplum Database
* Teradata Aster
* Teradata Data Warehouse
* Push-down processing for SAP HANA
* Using R with Array Databases (SciDB)

####Skills learned
The reader learns how to use packages such as RODBC or dplyr for generic SQL pass-through, and vendor-specific packages for SQL pass through.


###Chapter 3: Work with Structured Data in Hadoop and Spark – 30 pages
####Description
Building on the principles learned in the previous chapter, we cover push-down SQL and HiveQL for Hadoop and Spark.
####Level
MEDIUM
####Topics covered
* Using key R packages, such as RHIVE, Rimpala, Rpresto and SparkR
* Push-down SQL in Hadoop
* Apache Drill
* Apache Impala
* Cloudera Impala
* Facebook Presto
* Spark SQL and R

#### Skills learned
The reader learns how to use R packages for pass-through integration with SQL-on-Hadoop and Spark.


### Chapter 4: Work with Unstructured Data – 30 pages
#### Description
Working with R interfaces to Hadoop or NoSQL databases, the reader learns how to extract features from unstructured data for use in visualization or predictive modeling.
####Level
Medium
####Topics covered
* Push-down processing in NoSQL databases (RMongo, rhbase, etc)
* Push-down processing in Hadoop (rmr)
* Spark MLLib for feature extraction

#### Skills learned
The reader learns how to use platform-specific R packages to extract features from unstructured data, and also how to use SparkR to leverage Spark MLLib for the same task.


### Chapter 5: Work with Streaming Data – 30 pages
#### Description
In this chapter, we cover key concepts in streaming analytics, such as queries, sampling, filtering and windowing together with the required software and analytic techniques.  The chapter includes working with "pure" R packages and using the SparkR interface with Spark Streaming. 
#### Level
MEDIUM
####Topics covered
* Key concepts in streaming analytics
* Streaming analytics with R packages
    - stream
    - streamR
    - StreamingLM
* Using SparkR and Spark Streaming
* Streaming Linear Regression
* Streaming Logistic Regression
* Streaming k-Means

#### Skills learned
The reader learns how to work with "pure" R setups for streaming analytics versus and hybrid configurations based on Spark Streaming, and how to choose between the two.

###Chapter 6: GPU Computing in R – 20 pages
####Description
Recent advances in consumer computing hardware makes parallel computing capability accessible. Graphical Processing Units (GPUs) are great for applications that leverage parallel computing such as simulations.
####Level
ADVANCED
####Topics covered
* Principles of Parallel Computing
* GPU Accelerated R software stack
* R packages for High Performance computing with GPUs (eg. gputools, cudaBayesreg)
* Accelerating R Using CUDA Libraries
* Examples - Fast Fourier Transformation

####Skills learned
The reader learns when to apply parallel computing and how to accelerate applications using GPUs

###Chapter 7: Unsupervised Learning with R and H2O – 20 pages
####Description
As a first step in the discovery process, the data scientist performs unsupervised learning to reveal key patterns in the data.
####Level
ADVANCED
####Topics covered
* Summary Statistics
* Principal Components Analysis
* K-Means Clustering

####Skills learned
The reader learns how to use the R interface to H2O to work with unsupervised learning algorithms in the H2O machine learning library.


###Chapter 8: Unsupervised Learning with R and Spark – 40 pages
####Description
Building on principles defined in the previous chapter, this chapter covers use of unsupervised learning techniques in Apache Spark from the R interface.
####Level
ADVANCED
####Topics covered
* Basic Statistics
* Dimension Reduction Techniques:
* Principal Components Analysis
* Singular Value Decomposition
* Alternating Least Squares for Collaborative Filtering
* Clustering Techniques:
    - K-Means
    - Gaussian Mixture Models
    - Power Iteration Clustering
    - Latent Dirichlet Clustering
* FP-Growth for Frequent Pattern Mining

####Skills learned
The reader learns how to use the R interface to Spark for unsupervised learning techniques in the Spark machine learning library.


### Chapter 9: Supervised Learning with R and H2O – 30 pages
####Description
After performing exploratory analysis, the reader is ready to train a series of predictive models using different techniques and specifications.  
####Level
ADVANCED
####Topics covered
* Generalized Linear Models
* Naïve Bayes Classifier
* Random Forests
* Gradient Boosted Regression and Classification
* Cox Proportional Hazards

####Skills learned
The reader learns how to implement a variety of machine learning techniques in H2O from the R interface. 


###Chapter 10: Supervised Learning with R and Spark – 30 pages
####Description
Building on the previous chapter, this chapter covers supervised machine learning with Spark and the SparkR interface.
####Level
ADVANCED
####Topics covered
* Linear Regression
* Logistic Regression
* Support Vector Machines
* Naïve Bayes Classifier
* Decision Trees
* Random Forests
* Gradient Boosted Trees

####Skills learned
The reader learns how to implement a variety of machine learning techniques in Apache Spark from the R interface. 

### Chapter 11: Deep Learning with R and H2O – 30 pages
####Description
Recent advancements in the ability of data scientists to model high-level abstractions in data (Deep Learning) has triggered new interest in the use of neural network technology.  In this chapter, we cover key concepts in neural networks and Deep Learning, and how to apply these concepts using R and H2O
####Level
ADVANCED
####Topics covered
* Key Concepts
* Neural Networks
* Deep Learning
* Working with R and H2O
* Specify model parameters
* Model training
* Model interpretation
* Working with R and Spark (placeholder1)

####Skills learned
The reader learns key Deep Learning concepts and how to implement them using SparkR and H2O's Neural Network algorithm.


###Chapter 12: Test and Evaluate Predictive Models – 20 pages
####Description
From the range of modeling experiments performed in the previous chapters, the analyst must now choose the model with the best overall performance across a range of measures.  In this chapter, we cover how to produce these measures in an R report or visualization.
####Level
ADVANCED
####Topics covered
* Model-specific measures of fit
* Generic models of fit, including AIC and BIC
* Measures of model lift (AOC, Gains)

####Skills learned
The reader learns how to use the R interface to Big Analytics platforms to generate model evaluation statistics and display the results in an R report or graph.


### Chapter 13: Deploy Predictive Models – 20 pages
#### Description
Predictive models produce value when they are deployed in production.  This chapter covers the tools and techniques to create a document or code that can be quickly imported and used by a scoring and decision engine.
#### Level
ADVANCED
####Topics covered
* Predictive Model Markup Language
* The RPMML package
* Model export from Spark, H2O and MPP databases

####Skills learned
The reader learns how to convert a predictive model selected in the previous chapter into a PMML document or other executable.


###Chapter 14: Next Steps – 20 pages
####Description
This chapter brings the book to a close and encourages the reader to apply lessons learned.
####Level
BASIC
####Topics covered
* Review key points covered in the book
* Suggest next steps
* Point the reader to additional sources for help
* Appendices

#### Skills learned
N/A

Total Number of pages: 390