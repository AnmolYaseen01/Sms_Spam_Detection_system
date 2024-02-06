# SMS Spam Detection System

![SMS Spam Detection System Interface](https://github.com/AnmolYaseen01/Sms_Spam_Detection_system/blob/main/Sms%20Spam%20Detection%20system/Screenshot.png?raw=true)

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Web Application](#running-the-web-application)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview
The SMS Spam Detection System is a machine learning project designed to classify SMS messages into 'ham' (legitimate messages) or 'spam'. It leverages natural language processing (NLP) techniques and the Multinomial Naive Bayes algorithm to achieve high precision and accuracy, particularly crucial in the context of an imbalanced dataset where maintaining the reliability of legitimate message classification is paramount. This project aims to enhance communication security and efficiency by effectively filtering out spam messages.

## Features
- **Exploratory Data Analysis (EDA):** Initial analysis of the dataset to understand message characteristics.
- **Data Preprocessing:** Includes stemming, removal of stopwords, punctuation, and non-alphabetic characters.
- **Feature Engineering:** Utilizes TF-IDF vectorization for converting text to a numerical format suitable for machine learning models.
- **Visualization:** Frequency visualization of the most common words in ham and spam messages and the creation of word clouds.
- **Model Training and Evaluation:** Application of the Multinomial Naive Bayes algorithm, selected for its superior precision and accuracy.
- **Web Application:** A Streamlit-based web interface for users to input messages and receive instant classification predictions.

## Technologies Used
- Natural Language Toolkit (NLTK)
- Pickle
- Collections
- NumPy
- Pandas
- Scikit-learn
- Stopwords
- WordCloud
- String
- Streamlit for web application deployment

## Getting Started

### Prerequisites
Ensure you have Python installed on your system. This project was developed using Python 3.8. It's recommended to use a virtual environment for this project to manage dependencies effectively.

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/Anmol_Yaseen/sms-spam-detection-system.git
   ```
2. Navigate to the project directory:
   ```
   cd sms-spam-detection-system
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

### Running the Web Application
1. Start the Streamlit application:
   ```
   streamlit run app.py
   ```
2. The application should now be running on http://localhost:8501 or another port if specified. You can input SMS messages to classify them as ham or spam.

## Usage
The web interface is straightforward to use:
- Navigate to the provided URL after starting the application.
- Enter the SMS message you wish to classify in the input field.
- Click the "Predict" button to see the classification result.

## Contributing
Contributions to the SMS Spam Detection System are welcome. Please follow the standard fork and pull request workflow. If you plan on adding a new feature or fixing a bug, please open an issue first to discuss your ideas.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- The dataset used for training the model was sourced from the UCI Machine Learning Repository.
- Thanks to the various Python libraries that made this project possible.
```

### Note on Image Integration

In the markdown above, I included a placeholder for the image path. However, the path `C:\Users\Admin\Documents\GitHub\SmsSpamDetectionSystem\interface_screenshot.png` indicates a local file system path, which will not work on GitHub. To display an image in a GitHub README file, the image needs to be hosted either within the repository itself (using a relative path) or at a publicly accessible URL. 
