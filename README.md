# Fake News Detection

This project is a web application for detecting fake news using a machine learning model. The app is built with Streamlit and uses a pre-trained Logistic Regression model and a TF-IDF vectorizer to classify news as real or fake.

## Features

- Simple web interface for fake news detection
- Input news text and get instant prediction
- Utilizes machine learning (Logistic Regression)
- Pre-trained model and vectorizer included

## Requirements

- Python 3.10+
- Streamlit
- scikit-learn
- joblib

Install dependencies with:

```bash
pip install -r requirements.txt
```

## Usage

To run the app, use the following command:

```bash
streamlit run app.py
```

This will start a local web server. Open the provided URL in your browser to use the app.

## Files

- `app.py` : Main Streamlit application
- `lr_model.jb` : Pre-trained Logistic Regression model
- `vectorizer.jb` : Pre-trained TF-IDF vectorizer
- `requirements.txt` : Python dependencies

## Notes

- The model and vectorizer were trained with scikit-learn 1.0.2. If you encounter version warnings, try to match the scikit-learn version or retrain the model.
- For best results, use the app in a virtual environment.

## License

MIT License
