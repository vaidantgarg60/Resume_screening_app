📄 Resume Screening App
A simple and interactive Streamlit web application that classifies uploaded resumes (PDF, DOCX, TXT) into job categories using Machine Learning.

🚀 Features
🧠 Predicts resume category using a pre-trained ML model

📄 Supports PDF, DOCX, and TXT formats

🧼 Cleans and processes resume text

✅ Easy-to-use Streamlit interface

📁 File Structure
bash
Copy
Edit
Resume_screening_app/
├── app.py                # Main Streamlit app
├── clf.pkl               # Trained classification model
├── tfidf.pkl             # TF-IDF vectorizer
├── encoder.pkl           # Label encoder
├── requirements.txt      # List of dependencies
└── venv/                 # Virtual environment (optional to include)
📦 Requirements
Install dependencies via terminal:

bash
Copy
Edit
pip install -r requirements.txt
Or manually:

bash
Copy
Edit
pip install streamlit scikit-learn python-docx PyPDF2
▶️ How to Run the App
In terminal:

bash
Copy
Edit
streamlit run app.py
Then go to http://localhost:8501 in your browser.

📌 Model Assumptions
The model (clf.pkl) was trained on cleaned resume data and job categories.

tfidf.pkl is the TF-IDF vectorizer used during model training.

encoder.pkl is the label encoder mapping category numbers to names.

📚 Example Categories (if applicable)
Data Science

HR

Software Engineer

Web Developer

Business Analyst

You can update these based on your actual label classes.

🛡️ Disclaimer
This app is for educational/demonstration purposes only. Accuracy depends on the quality of training data and resume formatting.
