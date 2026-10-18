# Email Spam Classifier

A machine learning-based web application that classifies email messages into **Spam** or **Ham (Safe)**. Built with Python and Streamlit, this tool utilizes a trained classification model to detect unwanted or fraudulent emails in real-time.

## Features
- **User-Friendly Interface:** Simple and clean web application developed using Streamlit.
- **Real-Time Analysis:** Instantly processes input text and displays the classification result.
- **Accurate Predictions:** Uses a pre-trained Machine Learning model (`scikit-learn`) for reliable detection.

## Tech Stack
- **Language:** Python
- **Libraries:** Streamlit, Scikit-learn, Pandas, Pickle, nltk
- **Deployment:** Streamlit Community Cloud

## How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
