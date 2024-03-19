
# SMS Spam Detection

This project aims to detect spam SMS messages using machine learning algorithms. The dataset used for training and testing contains SMS messages labeled as either spam or non-spam (ham). We'll be using Support Vector Machine (SVM) and Logistic Regression algorithms for classification.

## Dataset

The dataset used in this project is obtained from [Kaggle]([link_to_the_dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset?resource=download)). It contains two columns: `labels` and `text`. The `labels` column indicates whether the SMS is spam or ham, while the `text` column contains the actual SMS message.

## Getting Started

To get started with this project, you'll need Python and the following libraries installed:

- pandas
- numpy
- matplotlib
- scikit-learn

You can install these libraries using pip:

```
pip install pandas numpy matplotlib scikit-learn
```

## Usage

1. Clone the repository:

```
git clone https://github.com/your_username/sms-spam-detection.git
```

2. Navigate to the project directory:

```
cd sms-spam-detection
```

3. Run the `sms_spam_detection.py` script:

```
python sms_spam_detection.py
```

## Results

After running the script, you'll see the accuracy scores, confusion matrices, and classification reports for both SVM and Logistic Regression models.

## Contributors

- [Victor Emuchay](https://github.com/Victor7615/NLP_For_Spam_and_Ham-/new/main?filename=README.md)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

