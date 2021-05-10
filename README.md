# sentiment_analysis_twitter
In this project, six emotions are analyzed and detected from textual data. This emotions are sadness, anger, love, surprise, fear, and joy.

In this project, I have done:
1. Data exploration (twitter dataset is used provided by Saravia et al. (2018))
2. Dataset cleansing
  i. Removal of special characters from sentences
  ii. Removal of stop words (is, am, are, the, has, have etc.)
  iii. Stemming: Process of reducing inflected words to their stem word (for example: stem for thinks,
thinking and thought is think)
3. Tokenization (Converting of textual data to numeric data).
4. Padding (To equalize the length of all sentences)
5. Model training and testing
  i. Using simple LSTM (a deep recurrent neural network) architecture using TensorFlow
  ii. Validation and testing

The whole project along with its code is provided in the attached HTML file.
