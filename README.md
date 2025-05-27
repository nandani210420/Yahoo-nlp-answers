Yahoo Answers Classification using Deep Learning
Goal
The goal of this project is to create a deep learning model to analyze the Yahoo Answers.

Dataset
The dataset for this project is taken from the Kaggle dataset website. Here is the link for the dataset: https://www.kaggle.com/datasets/yacharki/yahoo-answers-10-categories-for-nlp-csv

What Have I Done?
Imported all the required libraries and dataset for this project.

Exploratory Data Analysis and Visualizing different aspects of the dataset.

Finding number of observations and outliers in the dataset.

Plotting different attributes of the dataset.

Preprocessing of the dataset:

lower case the text

removing punctuations

removing stopwords

lemmatization

removing HTML syntax or URL's

stripping the extra spaces

applying contraction

Tokenization of data and applied text to sequence

Applying Deep Learning algorithms for the Model Creation such as CNN and LSTM.

Libraries used:
numpy

pandas

matplotlib

seaborn

sklearn

os

time

Keras

TensorFlow

Contractions

Visualization of question lengths per category:
(Implicitly, a visualization would be here)

Model Creation:
LSTM gave more accuracy than CNN.

CNN Performance Plot:
(Implicitly, a plot would be here)

LSTM Performance Plot:
(Implicitly, a plot would be here)

Hence, we have trained two neural network models: LSTM (Accuracy: 46.26%) and CNN (38.97%)
