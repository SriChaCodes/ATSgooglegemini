# ATS Resume Expert

This repository contains a Streamlit web application designed for leveraging Google's Generative AI model (Gemini) to analyze and evaluate resumes against job descriptions. The application allows users to upload a resume in PDF format, input a job description, and obtain insights such as professional evaluations or percentage match with the specified job requirements.

## Prerequisites

Before running the application, ensure you have the required dependencies installed. You can install them using the following command:

```bash
pip install -r requirements.txt
```

# Additional Configuration

## Google API Key Setup
Before running the application, you need to set up a Google API Key and add it to your environment variables or a `.env` file.

```env
GOOGLE_API_KEY=your_google_api_key
```
## How to Run

To launch the Streamlit app, run the following command in your terminal:

```bash
streamlit run app.py
```
## How to Run

This will start a local development server, and you can access the app by opening your web browser and navigating to the provided URL.

## Application Features

### 1. Job Description and Resume Upload
- Enter the job description in the provided text area.
- Upload a resume in PDF format using the file uploader.

### 2. Resume Analysis Options
#### a. Professional Evaluation
- Click the "Tell Me About the Resume" button to receive a professional evaluation of the candidate's profile against the job description.
- The analysis will highlight strengths and weaknesses in relation to the specified job requirements.

#### b. Percentage Match
- Click the "Percentage match" button to get a percentage match of the resume with the job description.
- The output will include the percentage match, keywords missing, and final thoughts.

## Contributions

Contributions to this project are welcome! If you have ideas for improvements or new features, feel free to open an issue or create a pull request.

To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your fork.
5. Open a pull request.

## Important Notes

- Ensure that the uploaded resume is in PDF format.
- Google API Key is required for utilizing the Gemini Generative AI model.

Feel free to explore and enhance the functionality of the application to suit your specific needs. If you encounter any issues or have suggestions for improvements, please open an issue in the repository.

Happy analyzing!



