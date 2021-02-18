# Identify major themes/topics across a collection of BBC news articles using topic modeling techniques.

Problem Statement - Identify major themes/topics across a collection of BBC news articles using topic modeling techniques.

<b>Data Summary</b> - The dataset contains a set of news articles for each major segment consisting of business, entertainment, politics, sports and technology. Total of 2225 articles are there in the dataset from the BBC news website corresponding to stories in five topical areas from 2004-2005. Need to create an aggregate dataset of all the news articles and perform topic modeling on the dataset and verify whether these topics correspond to the different tags available or not.

<b>Aproach</b> -

Merged all the articles to create the dataset with two columns. One column consists of article news and other with corresponding topics.
Applied various data preprocessing techniques to clean the data. Used lemmatization along with multiple libraries to remove stopwords.
Created features such as length, total words and average words of each article to get better insights of data.
Checked distribution of each topic using wordcloud so to compare model output clusters/topics to given topics.
Using TF-IDF vectorizer, converted bag of words model to sparse matrix which to be used for modeling.
Implemented several topic modeling techniques such as Latent Dirichlet Allocation (LDA), Latent Semantic Analysis (LSA) and Non-negative Matrix Factorization (NMF).
Checked model performance by visualizing model output clusters/topics using tools such as pyLDAvis, t-SNE Clustering and wordcloud.
Assigned respective clusters to topics as given initially (business, entertainment, politics, sports, technology), according to words it consists of.
Conclusion - Non-negative Matrix Factorization (NMF) showed best performance to properly segregate the articles into given 5 topics.

<b>Challenges</b> -

Due to large number of text files, data importing and some data cleansing tasks took longer time to excecute.
Limited visualization techniques restricted evaluation of slightly mixed topics.
Scope of Future Work -

Using LDA through Gensim library or other topic modeling techniques.
Implementing neural network with word2vec.
