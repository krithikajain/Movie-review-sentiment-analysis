# Movie-review-sentiment-analysis

### Overview
Movie Review Classification is implemented using the k-Nearest Neighbor (k-NN) algorithm to predict sentiments (positive or negative) for 25,000 movie reviews. The implementation involved loading and preprocessing datasets, experimenting with k-NN classifiers, exploring different vectorization techniques, and optimizing model parameters.

### Approach
🐥 Loaded and preprocessed datasets by splitting reviews and sentiments, applying regular expressions, and utilizing NLTK for stopword removal, stemming, and lemmatization

🐥 Experimented with in-built k-NN classifiers using Euclidean distance and Cosine Similarity, observing the efficiency of Cosine Similarity for text data.

🐥 Implemented a custom k-NN classifier to find the optimal nearest neighbor for accurate sentiment predictions.

🐥 Utilized TF-IDF vectorization to convert pre-processed data into numerical features, controlling parameters for optimal performance.

🐥 Explored train-test splits (80-20 ratio) to evaluate model performance before predictions on the test set.

🐥 Implemented Truncated SVD for dimensionality reduction, considering the sparse nature of the matrix.

🐥 Experimented with different values of K during the training phase and identified the optimal value for accurate predictions.

### Model Training and Evaluation
🐥 Trained the k-NN classifier on the training data and evaluated its performance on a validation set, measuring accuracy.

🐥 Conducted hyperparameter tuning and cross-validation on the validation dataset.
 
🐥 Made final predictions on the test data and compared accuracy with ground truth values.

🐥 Generated predictions were written to an output file named "test_predictions.txt."

### Results
🐥 Achieved an overall accuracy of 80%.

🐥 Successfully identified the optimal k value (157) for balanced and representative accuracy.

