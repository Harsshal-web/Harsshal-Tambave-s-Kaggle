# Harsshal-Tambave-s-Kaggle
</br>
Shivraj and Akshay worked on loading the Disaster Tweets dataset, exploring the data, preprocessing it, and loading a DistilBERT model from Keras NLP. They trained their own model by fine-tuning BERT and generated a submission file as part of the activity
</br>
</br>
Ajay Singh, Prerana, and Saurabh analyzed the train and test datasets, which include the following columns: id, keyword (a keyword from the tweet, which may be blank), location (the location the tweet was sent from, which may also be blank), text (the content of the tweet), and target (indicating whether the tweet is about a real disaster with 1 for yes and 0 for no).
</br>
</br>
Harshal and Roopam loaded a DistilBERT model from Keras NLP. They configured the BertClassifier with a preprocessor layer to handle raw inputs automatically during training, prediction, and evaluation. DistilBERT, an optimized version of BERT, retains 97% performance with 40% fewer parameters, runs 60% faster, and is streamlined by removing token-type embeddings, pooler, and halving the layers.
</br>
</br>
Rushikesh fine-tuned the BERT model for training and also plotted the confusion matrix to evaluate its performance.
</br>
