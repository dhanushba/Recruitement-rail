
# Recruitment Rail

**Recruitment Rail** is an advanced Applicant Tracking System (ATS) designed to revolutionize the recruitment process. By leveraging cutting-edge Natural Language Processing (NLP) techniques and Google Generative AI, this tool provides detailed resume evaluations and insightful job matching, enhancing the efficiency and accuracy of candidate screening.

## 🌟 Features

- **Resume Evaluation**: Analyze resumes with advanced NLP to match them against job descriptions effectively.
- **Keyword Matching**: Identify and highlight key skills and keywords in resumes relative to specific job descriptions.
- **Semantic Analysis**: Understand and assess the contextual relevance of resume content to job requirements.
- **User-Friendly Interface**: Developed with Streamlit, the web-based application offers an intuitive and interactive user experience.

## 🛠️ Technologies

- **Languages**: Python
- **Frameworks and Libraries**: Streamlit, Google Generative AI
- **Algorithms**: Natural Language Processing (NLP), Keyword Matching, Semantic Analysis

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Google Generative AI API Key
- Required Python libraries (as listed in `requirements.txt`)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/dhanushba/Recruitement-rail.git
   cd recruitment-rail
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables**:
   - Create a `.env` file in the root directory.
   - Add your Google API key:
     ```makefile
     GOOGLE_API_KEY=your_google_api_key_here
     ```

4. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

## 🎯 Usage

1. **Input the Job Description**: Paste the job description into the provided text area.
2. **Upload a Resume**: Upload a resume in PDF format.
3. **Analyze**: Click "Submit" to receive a detailed analysis, including keyword matching and percentage alignment with the job description.

## 🤝 Contributing

We welcome contributions! Feel free to submit issues or pull requests to enhance the functionality and performance of this application.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


bash
Copy code
streamlit run app.py
Usage
Paste the Job Description into the provided text area.
Upload a Resume in PDF format.
Click "Submit" to receive a detailed analysis, including keyword matching and percentage alignment with the job description.
Contributing
Feel free to submit issues or pull requests. Contributions are welcome to enhance the functionality and performance of the application.

License
This project is licensed under the MIT License. See the LICENSE file for details.
