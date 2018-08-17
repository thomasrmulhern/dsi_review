Review Session Questions
AWS/Pandas/SQL:

(?, ?) Explain how to get Pandas up and running with data on an AWS server.

1. Log into your AWS account and make sure the region option in the top right corner is the correct location.
2. Click on EC2 in the top left area, that will you bring you to the EC2 dashboard. Click on “Launch Instance.”
3. Choose Ubuntu Amazon Machine Image (AMI).
4. Select instance type.
5. Name your instance and a new security group.
6. Create a new key pair if you don’t already one or if you prefer using a different one than your others.
7. After creating the key pair, download its .pem file to your computer and place it in a folder; make the .pem file read only with the command chmod 400 [filename]
8. Review your instance details and launch your instance.
9. Retrieve the IP address from the EC2 dashboard and access it with:
  ssh -i ~/.ssh/name_pem_file.pem ubuntu@ip address.
10. Install ipython and pandas with apt-get:
  sudo apt-get update
  sudo apt-get install ipython python-pandas

(?, ?) Explain data subsetting in pandas using, .iloc, .loc, and and boolean indexing therein.
(?, ?) Show us your top 10 most useful commands in Pandas.  
(?, ?) Explain attaching (S3) storage to an AWS server and uploading data to it.
(?, ?) Explain how to set up an SQL server on AWS.
(?, ?) Explain subqueries and the use of temporary tables.



(?, ?) Compare group by syntax between Pandas and SQL, highlighting the difference between associated SQL where clauses and having clauses.
(?, ?) Explain the types of joins in SQL (inner, outer, left, right) and compare join syntax between Pandas and SQL.
Probability/Statistics/(A/B)Testing/Bayesian Analysis:

(?, ?) Compare and contrast three common continuous distributions, and three common discrete distributions.
(?, ?) Explain the difference between sample statistics and population parameters, and give a few examples.
(?, ?) Explain the difference between a joint distribution, and conditional distribution and a marginal distribution, and their respective roles in Bayes' theorem.
(?, ?) Explain the steps to perform a hypothesis test.
(?, ?) Explain the steps to perform a power calculation.
(?, ?) Compare and contrast CLT and bootstrapping confidence intervals.
(?, ?) Expound upon the Bayesian philosophy relative to the frequentist approach based on p-values.
(?, ?) Show what the multi-armed bandit is, how it's implemented, and why it works.
Parametric/Non-parametric/Ensemble/Overfitting:

(?, ?) Give examples of two parametric models and two non-parametric models, and compare and contrast the strengths of each.
(?, ?) Compare and contrast ensemble methods.
(?, ?) Compare and contrast linear and logistic regression models.
(?, ?) Explain stepwise selection in a linear regression model context.
(?, ?) Describe the issue of multicollinearity with particular attention to linear regression model contexts.
(?, ?) Contrast model bias, model variance and intrinsic variance; and discuss their relationship to underfitting and overfitting.
(?, ?) Discuss three ways to combat high model variance.
(?, ?) Discuss the issues and context of imbalanced classes classification.
SVMs/NNs/Profit Curves:

(?, ?) What are support vectors and what is the margin in SVM contexts?
(?, ?) What is the kernel trick?
(?, ?) In a NN, how do we initialize the weights and how do we train the weights?
(?, ?) Discuss activation and softmax functions in the NN context.
(?, ?) Describe the mechanics and role of convolutional kernel and max pooling layers in CNN contexts.
(?, ?) Distinguish a confusion matrix from a cost-benefit matrix.
(?, ?) Compare a profit curve to an ROC curve.
(?, ?) Discuss how multi-cass (>2 class) classification is done.
NLP/Clustering/Web:

(?, ?) What is text normalization?
(?, ?) Compare bag-of-words, binary bag-of-words and TF-IDF.
(?, ?) Why is Cosine Similarity (usually) a better choice of a distance metric for NLP instead of Euclidean Distance?
(?, ?) Comare and contrast k-means with hierarchical clustering.
(?, ?) Explain two ways to choose k.
(?, ?) Explain how Naive Bayes predicts classifications in NLP contexts.
(?, ?) Tell us the most useful things to know about in order to do web scrapping.
(?, ?) Show off your Rest API, describing how it works.
Model Fitting/Recommenders/easter eggs:

(?, ?) Compare Maximum Likelihood and Method of Moments.
(?, ?) Explain loss and cost functions and model fitting.
(?, ?) Compare and contrast gradient decent and gradient boosting.
(?, ?) Explain why gradient boosting can outperform random forests.
(?, ?) Explain how PCA can be used for dimensionality reduction
(?, ?) Compare PCA/SVD, NMF, and UV decomposition.
(?, ?) Discuss how to evaluate recommender system performance.
(?, ?) Tell us what a RNN is!
