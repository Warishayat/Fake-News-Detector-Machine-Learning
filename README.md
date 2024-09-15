# Fake News Detector

This project is a Fake News Detector that uses various machine learning models to classify news articles as real or fake. The primary focus is on comparing the performance of different classifiers, including Logistic Regression, Support Vector Classifier (SVC), Random Forest, and Decision Tree. The dataset used contains news articles with corresponding labels indicating whether they are real or fake.

Dataset Link: https://www.kaggle.com/datasets/jillanisofttech/fake-or-real-news
<br>
NoteBook Link: https://github.com/Warishayat/Fake-News-Detector-Machine-Learning

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started, clone the repository and install the required packages:

```bash
git clone https://github.com/Warishayat/Fake-News-Detector-Machine-Learning
cd fake-news-detector
pip install -r requirements.txt
```

## Usage

1. **Preprocess the Data**: The text data is preprocessed by converting to lowercase, removing punctuation, and stemming the words.

2. **Split the Data**: The data is split into training and testing sets.

3. **Convert Text to Numeric Form**: TF-IDF is used to convert textual data into numeric form.

4. **Train and Evaluate Models**: Different models are trained and their performance is evaluated but found the losgiftic regression best.

### Preprocessing

- Convert text to lowercase.
- Remove punctuation.
- Stem the words to their root form.

### Splitting the Data

- The dataset is split into training and testing sets using an 80-20 split.

### Converting Text to Numeric Form

- TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert the textual data into numeric form.

### Training and Evaluating Models

- **Logistic Regression**: This model is trained on the training data and evaluated on the test data.

```python
Model1 = LogisticRegression()
Model1.fit(X_train, y_train)

y_pred = Model1.predict(X_test)
```

### Performance Metrics

The following metrics are used to evaluate the performance of the models:

- **Accuracy**: The proportion of correctly classified instances.
- **Confusion Matrix**: A table used to describe the performance of a classification model.
- **Precision**: The ratio of correctly predicted positive observations to the total predicted positives.
- **Recall**: The ratio of correctly predicted positive observations to all observations in the actual class.
- **F1 Score**: The weighted average of Precision and Recall.

### Logistic Regression Performance Metrics

- **Accuracy**: 0.8216
- **Confusion Matrix**: 
  ```
  [[568  96]
   [130 473]]
  ```
- **Precision**: 0.8313
- **Recall**: 0.7844
- **F1 Score**: 0.8072

## Models

- **Logistic Regression**
- **Support Vector Classifier (SVC)**
- **Random Forest**
- **Decision Tree**

## Results

After evaluating different models, Logistic Regression provided the best results with the highest accuracy.

## Contributing

Feel free to fork this repository and contribute by submitting a pull request.

## License

This project is licensed under the MIT License.

Feel free to Approach me anytime anywhere at Warishayat666@gmail.com

If you like my Work Kindly hit the #follow button & #Star button also.

---
