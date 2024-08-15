Here's an enhanced, professional version of the README with the requested changes:

# Phishing URL Checker

## Objective

This project aims to develop and compare machine learning models and deep neural networks for predicting phishing websites. We use a curated dataset of both phishing and benign URLs, extracting essential features from URL and website content. The performance of each model is measured and compared to identify the most effective approach for phishing detection.

## Installation

To set up the project environment, follow these steps:

1. Fork and clone this repository
2. Navigate to the project directory
3. Run the following command to install required packages:

```bash
pip install -r requirements.txt
```

## Technologies Used

<img src="https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg" width=200> <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width=200>
<img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" width=100>
<img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcScq-xocLctL07Jy0tpR_p9w0Q42_rK1aAkNfW6sm3ucjFKWML39aaJPgdhadyCnEiK7vw&usqp=CAU" width=200>

## Feature Extraction

The system collects URLs from user input on the web interface. It then extracts relevant features from these URLs based on:
- Domain characteristics
- HTML content
- Address bar attributes

These features are crucial for training and evaluating our machine learning models.

## Machine Learning Models

We compare various machine learning models to predict whether a URL is a phishing site. The model with the highest accuracy is selected for final implementation. URLs are categorized as either "phishing" or "legitimate", with results displayed on the webpage.

For detailed implementation, please refer to `Phishingproject.ipynb`.

## Results

Performance comparison of various models used for URL detection:

| ML Model                     | Accuracy | F1 Score | Recall | Precision |
|------------------------------|----------|----------|--------|-----------|
| Gradient Boosting Classifier | 0.974    | 0.977    | 0.994  | 0.986     |
| CatBoost Classifier          | 0.972    | 0.975    | 0.994  | 0.989     |
| Multi-layer Perceptron       | 0.969    | 0.973    | 0.995  | 0.981     |
| Random Forest                | 0.967    | 0.971    | 0.993  | 0.990     |
| Support Vector Machine       | 0.964    | 0.968    | 0.980  | 0.965     |
| Decision Tree                | 0.960    | 0.964    | 0.991  | 0.993     |
| K-Nearest Neighbors          | 0.956    | 0.961    | 0.991  | 0.989     |
| Logistic Regression          | 0.934    | 0.941    | 0.943  | 0.927     |
| Naive Bayes Classifier       | 0.605    | 0.454    | 0.292  | 0.997     |

## Project Interface

### 1. Home Page
![Home Page](https://github.com/Mugeshcybersecurity/Phishing-Url-Checker/blob/main/Output-samples/URL.png)

- Clean, user-friendly interface
- Prominent URL input field for easy submission
- Clear navigation menu for accessing other sections
- Informative header explaining the purpose of the tool

### 2. Result Page
![Result Page](https://github.com/Mugeshcybersecurity/Phishing-Url-Checker/blob/main/Output-samples/result.png)

- Clear presentation of the URL analysis result
- Visual indicator of the phishing probability
- Option to check another URL for continuous use

### 3. More Tab
![More Tab](https://github.com/Mugeshcybersecurity/Phishing-Url-Checker/blob/main/Output-samples/mOREpng.png)

- Additional resources for user education and engagement
- Option to report suspected phishing sites
- Link to Google Safe Browsing for further verification
- Interactive quiz to test and improve phishing awareness

### 4. Case Study Tab
![Case Study Tab](https://github.com/Mugeshcybersecurity/Phishing-Url-Checker/blob/main/Output-samples/CASE%20STUDY.png)

- Comprehensive collection of real-world phishing case studies
- Detailed descriptions of previous phishing incidents
- Analysis of tactics used by phishers
- Lessons learned and prevention strategies

## Conclusion

- This project provides valuable insights into the features that significantly impact a model's ability to detect phishing URLs.
- Key features such as "HTTPS," "AnchorURL," and "WebsiteTraffic" play crucial roles in URL classification.
- The Gradient Boosting Classifier achieved the highest accuracy at 97.4%, demonstrating its effectiveness in reducing the risk of malicious attachments.
- The user-friendly interface and educational components make this tool valuable for both technical and non-technical users.

## Contributing

We welcome contributions to improve this project. Please feel free to submit issues and pull requests.
