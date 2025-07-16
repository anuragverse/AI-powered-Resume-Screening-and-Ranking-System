# 🧠 AI-powered Resume Screening and Ranking System

This is a Streamlit-based web application that uses **Natural Language Processing (NLP)** to screen and rank resumes based on their similarity to a provided job description. It utilizes **TF-IDF vectorization** and **cosine similarity** from `scikit-learn` to compute relevance scores, helping recruiters shortlist the most suitable candidates efficiently.

## ✅ Features

- 🔍 Paste or enter any job description  
- 📄 Upload multiple resumes (PDFs)  
- 🧠 Extract and process resume content using NLP  
- 📊 Score and rank resumes based on match with the job description  
- 📈 Display sorted results in a clean, tabular format  

## 📁 Project Structure

```
AI-powered-Resume-Screening-and-Ranking-System/
 ┣ main.py             # Main Streamlit app
 ┣ requirements.txt    # List of dependencies
 ┗ README.md           # Project documentation
```

## 🔧 Installation Process

Follow these steps to set up and run the project on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/anuragverse/AI-powered-Resume-Screening-and-Ranking-System.git
cd AI-powered-Resume-Screening-and-Ranking-System
```

### 2. Install Required Dependencies

Using `requirements.txt`:

```bash
pip install -r requirements.txt
```
Or manually:

```bash
pip install streamlit PyPDF2 pandas scikit-learn
```

### 5. Run the Application

Use Streamlit to launch the app:

```bash
streamlit run main.py
```

This will open the app in your default browser at:

```
http://localhost:8501
```

## 🧪 Example Workflow

1. 📝 Enter Job Description in the text area.  
2. 📤 Upload Resume PDFs using the uploader.  
3. 🔍 The app analyzes and compares resume content to the job description.  
4. 📈 A ranked list of resumes is displayed based on similarity scores.  

## ⚙️ Tech Stack

- **Frontend & App Framework**: Streamlit  
- **PDF Processing**: PyPDF2  
- **Data Handling**: Pandas  
- **NLP & Similarity Analysis**: Scikit-learn  

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.
