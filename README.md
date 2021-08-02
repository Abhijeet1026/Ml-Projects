This file contains information about all the machine learning projects.

1. Personalized cancer diagnosis

   A Machine learning Case Study to detect type of mutation in a gene using gene, variation, and text.
 - Classify the given genetic variations/mutations based on evidence from text-based clinical literature.
 - In this case study, we need to find the type of the mutation gene, given variation, some text data, and 
  gene from public research.
 - Performed univariate analysis, data cleaning then converted text to vector using TFIDF.
 - Finally predicted the mutation by training 3k points and reduced log loss from 2.554 to 0.96

2. Social Network Graph Link Prediction

   A Machine Learning case study to predict links in a social graph to recommend friends/connections/followers.
 - Engineered 30 graph features.
 - Trained Random forest and XGBOOST Models.
 - Achieved the highest F1-Score using of 0.926.

3. Quora Question Pair Similarity Problem

   The Objective of the Project was to identify which questions asked on Quora are duplicates of questions that have already been asked.
 - Used approximately 300k  questions pair dataset.
 - Used extensive natural language processing to preprocess the question.
 - Trained logistic regression, linear SVM and XGBOOST models.
 - Reduced the test log-loss from 0.88 to 0.34.
 - Best Performing model is XGBOOST.

4. Taxi Demand Prediction in New York
   
   A case study to forecast Pickup Densities for Yellow Taxi Services In New York City – Using Machine Learning Techniques
 -	Performed data preparation by removing the outliers from features (latitude, longitude, speed, trip times, etc.)
 -	Segmented the data into regions using the clustering technique
 -	Created Fourier features such as Amplitude, Frequency and also used Exponential average, Double Exponential Average as the input data to the model
 -	Achieved the lowest Mean Absolute Percentage Error of 10.16% with the Xgboost model

5. Stack Overflow Tag Predictor

   A Machine learning Case study to suggest the tags based on the content that was there in the question posted on Stack overflow
 - Tags were analyzed by univariate analysis technique
 -	Plotted Word Cloud using most frequent tags in the dataset
 -	Data cleaning and preparation was done by removing duplicates, code – snippets, special characters, Stopwords, HTML Tags, etc.
 -	Converted text in vectors with the help of TF-idf technique
 -	Achieved the lowest F1 – Micro by using Linear SVM with L1 regularisation

6. Sentiment Classification on Yelp Data

   The Objective of this Machine Learning project was to perform the sentiment classification on the online reviews 
 -	Data preprocessing was performed to remove contractions, digits, emoticons, special characters, stop words from the reviews
 -	Performed univariate and bivariate analysis to understand the data better
 -	Feature Engineering was performed by converting text into vectors using SpaCy library
 -	Since the dataset was highly imbalanced, therefore oversampling technique was used to balance the dataset
 -	Best performing model Support Vector Machine with F1 Score of 90.08 %

7. Microsoft Malware Detection

   The Objective of this Machine learning project was to identify whether a given piece of software/file is a Malware 
 -	Performed the Univariate Analysis of the data
 -	Features - Size of the byte and ASM files, Unigram of prefixes, opcodes, registers, keywords were extracted from ASM files
 -	Advanced Features – bigram of hexadecimal code from byte file, Image features from ASM files were also extracted
 -	Achieved the lowest Multi Class log loss of 0.01 using Xgboost model









