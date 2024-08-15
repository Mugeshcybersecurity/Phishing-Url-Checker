# Phishing URL Checker

## Overview

The Phishing URL Checker is an advanced cybersecurity tool designed to identify and flag potentially malicious websites. Leveraging state-of-the-art machine learning algorithms and deep neural networks, this project aims to provide a robust defense against phishing attacks, one of the most common forms of cyber threats.

## Objective

Our primary goal is to develop and compare various machine learning models for accurately predicting phishing websites. By analyzing a curated dataset of both legitimate and phishing URLs, we extract critical features from URL structures and website content to train our models. This approach allows us to achieve high accuracy in distinguishing between safe and malicious web addresses.

## Key Features

- Real-time URL analysis
- Machine learning-powered prediction
- User-friendly web interface
- Educational resources on phishing prevention
- Case studies of real-world phishing incidents

## Technology Stack

<div align="center">
  <img src="https://www.python.org/static/community_logos/python-logo-generic.svg" width="200">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg" width="200">
  <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width="200">
</div>
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" width="100">
  <img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width="200">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcScq-xocLctL07Jy0tpR_p9w0Q42_rK1aAkNfW6sm3ucjFKWML39aaJPgdhadyCnEiK7vw&usqp=CAU" width="200">
</div>

- **Python**: Core programming language
- **NumPy**: Numerical computing
- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Data visualization
- **Scikit-learn**: Machine learning algorithms
- **TensorFlow**: Deep learning capabilities

## Installation

To set up the project environment:

1. Clone the repository:
   ```
   git clone https://github.com/YourUsername/Phishing-URL-Checker.git
   ```
2. Navigate to the project directory:
   ```
   cd Phishing-URL-Checker
   ```
3. Install required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the main application script:
   ```
   python app.py
   ```
2. Open your web browser and go to `http://localhost:5000`
3. Enter the URL you want to check in the provided input field
4. Click "Check URL" to receive the analysis results

## Model Performance

Our comparative analysis of various machine learning models yielded the following results:

| Model                        | Accuracy | F1 Score | Recall | Precision |
|------------------------------|----------|----------|--------|-----------|
| Gradient Boosting Classifier | 0.974    | 0.977    | 0.994  | 0.986     |
| CatBoost Classifier          | 0.972    | 0.975    | 0.994  | 0.989     |
| Multi-layer Perceptron       | 0.969    | 0.973    | 0.995  | 0.981     |
| Random Forest                | 0.967    | 0.971    | 0.993  | 0.990     |
| Support Vector Machine       | 0.964    | 0.968    | 0.980  | 0.965     |

The Gradient Boosting Classifier demonstrated superior performance, achieving 97.4% accuracy in phishing URL detection.

For more info check this Colab Link:
https://colab.research.google.com/drive/1giaCACgQFmh33_ycwz_voSnYKKaOeDgO?usp=sharing
## User Interface

### Home Page
![Home Page](https://github.com/Mugeshcybersecurity/Phishing-Url-Checker/blob/main/Output-samples/URL.png)

- Clean, intuitive design for easy URL submission
- Clear navigation to additional features

### Result Page
![Result Page](https://github.com/Mugeshcybersecurity/Phishing-Url-Checker/blob/main/Output-samples/result.png)

- Comprehensive analysis display
- Visual representation of phishing probability
- Detailed breakdown of decision factors

### Additional Resources
![More Tab](https://github.com/Mugeshcybersecurity/Phishing-Url-Checker/blob/main/Output-samples/mOREpng.png)

- Option to report suspected phishing sites
- Link to Google Safe Browsing
- Interactive phishing awareness quiz

### Case Studies
![Case Study Tab](https://github.com/Mugeshcybersecurity/Phishing-Url-Checker/blob/main/Output-samples/CASE%20STUDY.png)

- In-depth analysis of real phishing incidents
- Insights into phishing tactics and prevention strategies

## Key Findings

- Features like "HTTPS," "AnchorURL," and "WebsiteTraffic" are crucial in accurate URL classification.
- The Gradient Boosting Classifier outperformed other models, providing reliable phishing detection.
- A combination of machine learning and user education is essential for comprehensive phishing prevention.

## Future Enhancements

- Integration with browser extensions for real-time protection
- Incorporation of natural language processing for content analysis
- Development of an API for third-party integrations

## Contributing

We welcome contributions to enhance this project.
