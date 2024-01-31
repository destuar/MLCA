
# Spam Email Classifier

This project presents a Python-based spam email classifier using machine learning techniques. It employs the Gaussian Naive Bayes algorithm to distinguish between spam and non-spam (ham) emails. The classifier is trained and evaluated on pre-processed datasets containing both types of emails.

## Features

- **Dictionary Creation**: Builds a dictionary of the most common words found in the training emails.
- **Feature Extraction**: Extracts features from emails using word frequency relative to the dictionary.
- **Naive Bayes Classification**: Utilizes the Gaussian Naive Bayes model for categorizing emails.
- **Performance Metrics**: Calculates the accuracy of the classifier against a test dataset.

## Prerequisites

- Python 3.x
- NumPy
- scikit-learn

## Dataset

The classifier requires a dataset of emails categorized into 'spam' and 'non-spam'. These should be organized into separate directories for training and testing, with individual emails stored as separate files.

## Installation

1. Clone or download the repository.

## Usage

1. Set the directory paths for your training and testing datasets in the script (`TRAIN_DIR` and `TEST_DIR`).
2. Run the script to build the dictionary, extract features, train the model, and evaluate its performance.

## Structure

- `make_Dictionary(root_dir)`: Generates a word frequency dictionary from the training emails.
- `extract_features(mail_dir)`: Creates feature vectors and labels for training and testing based on email content.
- `TRAIN_DIR` & `TEST_DIR`: Directory paths for training and test datasets.
- Model Training and Evaluation: The script trains using the training data and assesses accuracy using the test data.

## Output

The script will output the progress of email processing, model training, and finally, the classifier's accuracy score on the test dataset.

## Authors

- Andrew Xu
- Yannick Angouo Lopes
- Diego Estuar

## License

This project is open-source and available under [LICENSE](LICENSE).

## Acknowledgments

Special thanks to all contributors and those who have provided valuable feedback and suggestions to improve this classifier.

---

This README offers a comprehensive overview and guide for the Spam Email Classifier. Ensure your datasets are correctly prepared and directory paths properly set for optimal use of the script.
