# Naive_Bayes_IMDb
Naive Bayes is a Probabilistic Classifier that returns the probability of a test point belonging to a class rather than the label of the test point. The basis of Naive Bayes is Baye's theorem which deals with three things:
1. Prior Probability: Historical Statistical Information. It can also be seen as the Base Rate. 
2. Posterior Probability: The probability of the event happening after a certain situation(the one that is being examined in the likelihood function) is introduced.
3. Likelihood: Information that is specific to the situation being examined. 
such that:
          Posterior = Prior * Likelihood Ratio
   ![image](https://github.com/cheshtadhingra/Naive_Bayes_Imdb/assets/71834443/34b057ab-e9d5-4dc9-8609-f8e5c04a8bf4)

The Naive Bayes text classification understands the data that you are going to work with and converts the document into the form of a vocabulary by removing stop words(the words that are grammatical and carry no significance whilst creating a vocabulary like is, and, or, etc.)

We convert the data we have into a 'Bag of words Representation' format which generally breaks down the sentences and creates a frequency table type of format! [image](https://github.com/cheshtadhingra/Naive_Bayes_Imdb/assets/71834443/3ce763c6-469f-4ac3-8a82-731870e85136)

Later on, we train the dataset on our MultinomialNaiveBayes/BinomialNaiveBayes classifier depending on the type of class labels, and calculate our evaluation metrics. 

I have tried to do a similar thing in this project taking the IMDb data to classify the documents into different labels. The test and train datasets were different available, so I didn't perform a train_test_split on the same. 
I achieved a sensitivity of 78%, a precision of 80%, and a recall score of 78%. 

I further plan on exploring the dataset more, removing some more data from my training dataset, and checking if the evaluation metrics get any better or not. 
