# Imagined-vs-Recalled-Memories-

## Introduction
This project explores the classification of narratives within the Hippocorpus dataset as either 'recalled' or 'imagined'. Utilizing advanced NLP techniques, including BERT embeddings and sentiment analysis, the study aims to distinguish between the nuanced aspects of human memory and imagination. The project unfolds in three phases, each building upon the last to refine the classification model.

## Dataset
The dataset consists of over 6,000 English short stories, diary-like in nature, from the Hippocorpus dataset. This provides a rich source for examining the nuances in human memory and imagination.

## Data Preprocessing and Feature Engineering
The project involves several preprocessing steps:

- **BERT Embeddings:** The story texts are initially processed to extract deep linguistic features using BERT embeddings, aiming to classify the narratives based solely on their textual content.

- **Additional Features:** The model is then enhanced by incorporating additional features from the dataset, including demographic information and event-related details, to provide broader contextual data for classification.

- **Sentiment Analysis:** Sentiment polarity of each story is computed and utilized as a feature, hypothesizing that emotional tone may be significant in differentiating between recalled and imagined stories.

## Model Development
The model development phase includes:

- **Initial Logistic Regression Model:** Utilizing logistic regression to classify stories based on BERT embeddings.

- **Enhanced Model with Additional Features:** Augmenting the model with additional features from the dataset to leverage a broader context.

- **Sentiment Analysis Integrated Model:** Incorporating sentiment analysis to add emotional context to the narrative features. A neural network with dense layers and dropout is constructed using TensorFlow and Keras to accommodate both BERT embeddings and sentiment analysis features.

## Results
The results from the three phases show:

- **Logistic Regression Model:** Demonstrated improvement in classification but indicated the need for more complex models for enhanced accuracy.

- **Enhanced Model with Additional Features:** Showed improved performance, suggesting the value of integrating broader contextual information.

- **Sentiment Analysis Integrated Model:** Highlighted the importance of emotional context in narrative classification.

## Conclusions
The progression through the project's phases reflects the complexity involved in distinguishing between recalled and imagined narratives. The incorporation of emotional context through sentiment analysis in the final phase underlines its importance in narrative classification. This exploration paves the way for future work, potentially involving more linguistic features and complex models to refine classification accuracy.
