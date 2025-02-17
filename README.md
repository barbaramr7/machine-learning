# machine-learning

📰 Fake News Detection using Supervised Machine Learning


📌 Overview


This project applies supervised machine learning techniques to build a classifier capable of detecting fake news. Using a dataset of news articles labeled as "fake" or "real," the model learns patterns to distinguish between the two categories.


📊 Dataset


The dataset consists of a collection of news headlines and articles in English, previously classified as either fake or real. It was obtained from a public source.


🔍 Approach


The project follows these steps:


📥 Data Collection: The dataset is loaded and analyzed to understand its distribution.


🛠 Feature Extraction:


📦 Bag of Words (BoW): Using CountVectorizer to convert text into numerical representations.


📈 TF-IDF (Term Frequency-Inverse Document Frequency): Using TfidfVectorizer to weigh words by importance.


🤖 Model Training: Supervised learning algorithms from scikit-learn are used to train the model.


📉 Evaluation & Interpretation: Performance metrics are calculated to assess the classifier's accuracy and effectiveness.


🛠 Requirements


To run this project, install the necessary dependencies:

pip install pandas numpy scikit-learn matplotlib


🚀 Usage


Run the Jupyter Notebook to train and evaluate the fake news classifier:

jupyter notebook NLP_machine_learning.ipynb


🎯 Results


The trained model is evaluated on a test set, and key performance metrics such as accuracy, precision, recall, and F1-score are used to measure its effectiveness.


🙌 Acknowledgments


The dataset was sourced from a public repository.

The implementation is based on scikit-learn for machine learning tasks.


📜 License

This project is open-source and available under the MIT License.
