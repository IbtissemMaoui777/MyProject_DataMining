# MyProject_DataMining
***
***
## Extraction de tweets :
• Here is a way to extract tweets based on certain topics from Twitter API using the Tweepy library for example (Sport, Music, theater, Dance, Health, Cancer, DataSience).

• For using the Twitter API you need to have a developer access Twitter account. Request for the same it might take 2–3 hours to get an approval. Once, you’re done with the set up   create an app, in it, you will get Keys and tokens, which will help us retrieve data from Twitter.They act as login credentials.

• After getting access to Twitter data we’ll now create a file to save all the tweets in it for example (allTweets.csv).
***

## Preprocessing tweets (NLP):
• Cleaning up tweets (create  a function to clean the tweets(nlp_pipeline)).

• Install nltk.

• Importing needed librairies.

• Tokenization, lemmatization and stop words removal.

• Delete the duplicate lines using drop_duplicates().
***

## Classification of tweets:
• Defining the set of words ( Sport_related_words, Art_related_words, Health_related_words, DataSience_related_words).

• Preprocessing the sets (Tokenizing and removing stop words from the sets, Delete duplicates).

• Jaccard Similarity ('''Jaccard similarity is good for cases where duplication does not matter, 
   cosine similarity is good for cases where duplication matters while analyzing text similarity.
   For two product descriptions, it will be better to use Jaccard similarity as repetition of a word does not reduce their similarity.'''):

         ** Get_scores( Sport scores, Art scores, Health scores, DataSience scores).
         ** Assigning of classes to the tweets.
         ** Calculate the total number in each category.
  ***
## Kmeans:
• Using the elbow method to find the optimal number of clusters.

• Appending the WCSS to the list (kmeans.inertia_ returns the WCSS value for an initialized cluster).

• Fitting kmeans to dataset.

• Visualising the clusters.












 
   

