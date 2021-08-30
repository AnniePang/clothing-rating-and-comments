# clothing-rating-and-comments

Practice project to learn **Natural Language Processing (NLP) and Unsupervised Machine Learning.**

Tools: numpy, pandas, matplotlib, seaborn, wordcloud, sklearn especially with CountVectorizer, TfidfVectorizer, Kmeans, TSNE, NMF, TruncatedSVD, silhouette_score, MultinomialNB, LogisticRegression.

What I learned:

1. “Separation” of good and bad reviews using **clustering**: to separate out or find pattern of bad and good reviews for different products. Used KMeans, and also used inertia and silhouette scores as proxy to help me identify what is the best number of clusters I should use. Then using TSNE to help me visualize the clusters generated.
2. How to decide what stop words to use based on the context of your data and problem you want to solve, how to lemmatize, how to vectorize -- cleaned text data (Count Vectorizer and TF-IDF), how to reduce your dimensionality and avoid curse of dimensionality, and etc.

Link: https://drive.google.com/file/d/14PjtXp8BaXv04r4nI0eBTDmhq2pnpUEv/view?usp=sharing
