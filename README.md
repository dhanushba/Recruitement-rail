Recruitment Rail
Recruitment Rail is an advanced Applicant Tracking System (ATS) designed to enhance the recruitment process by providing detailed resume evaluations and job matching insights. Built using Streamlit and Google Generative AI, this tool helps streamline candidate screening and improve hiring efficiency.

Features
Resume Evaluation: Analyze resumes and match them against job descriptions using advanced NLP techniques.
Keyword Matching: Identify and highlight key skills and keywords in resumes relative to job descriptions.
Semantic Analysis: Understand and assess the contextual relevance of resume content to job requirements.
User-Friendly Interface: Interactive web-based application developed with Streamlit for ease of use.
Technologies
Languages: Python
Frameworks and Libraries: Streamlit, Google Generative AI
Algorithms: Natural Language Processing (NLP), Keyword Matching, Semantic Analysis
Getting Started
Prerequisites
Python 3.x
Google Generative AI API Key
Required Python libraries (listed in requirements.txt)
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/recruitment-rail.git
cd recruitment-rail
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Set Up Environment Variables:

Create a .env file in the root directory.
Add your Google API key:
makefile
Copy code
GOOGLE_API_KEY=your_google_api_key_here
Run the Application:

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
