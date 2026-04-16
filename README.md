# AI Resume Critiquer 

An AI-powered resume analysis web app built with **Streamlit** and **OpenAI API** that helps users improve their resumes with personalized, professional feedback.

##  Features

*  Upload resumes in **PDF** or **TXT** format
*  AI-generated resume analysis and suggestions
*  Role-specific recommendations based on target job title
*  Improve content clarity, impact, skills, and experience sections
*  Fast and simple Streamlit interface
*  Secure API key management using `.env`

---

##  Tech Stack

* **Python**
* **Streamlit**
* **OpenAI API**
* **PyPDF2**
* **python-dotenv**

---

##  Preview

Upload your resume, enter your target job role, and get instant AI feedback.

---

##  Project Structure

```bash
AI-Resume-Critiquer/
│── app.py
│── requirements.txt
│── .env.example
│── .gitignore
│── README.md
```

---

## Installation & Setup

### 1️. Clone the Repository

```bash
git clone https://github.com/your-username/AI-Resume-Critiquer.git
cd AI-Resume-Critiquer
```

### 2️. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️. Add Environment Variables

Create a `.env` file in the root folder:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

### 4️. Run the Application

```bash
streamlit run app.py
```

---

##  How It Works

1. Upload your resume file (**PDF/TXT**)
2. Enter the job role you are targeting *(optional)*
3. Click **Analyze Resume**
4. Receive AI-powered feedback instantly

---

##  AI Review Focus Areas

The app evaluates resumes based on:

* Content clarity and readability
* Skills presentation
* Experience descriptions
* Relevance to target role
* Improvement suggestions

---

## Security Note

Never upload your `.env` file or API key to GitHub.
Use `.env.example` for public repositories.

---

## Future Improvements

* Resume score out of 100
* ATS compatibility checker
* Download feedback as PDF
* Improved UI / dark mode
* Multi-language support
* Resume keyword optimization

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Open a Pull Request

---

## License

This project is licensed under the MIT License.

---

## Author

Developed by **Harathi**


