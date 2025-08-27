

# Resume.io

Resume.io is a modern, AI-powered resume analysis and enhancement web application built with React, Vite, and Tailwind CSS. It allows users to upload their resume (PDF), analyze it against a job description, receive ATS (Applicant Tracking System) scores, keyword matching, and personalized feedback using Google Gemini AI.

## Features

- Upload your resume in PDF format
- Extracts and analyzes resume content using AI
- ATS scoring and compatibility analysis
- Keyword matching with job descriptions
- Personalized feedback and enhancement suggestions
- Secure API key management via environment variables

## Getting Started

1. **Clone the repository:**
	```sh
	git clone https://github.com/adnanhussain8082/Resume.io.git
	cd Resume.io/rim
	```

2. **Install dependencies:**
	```sh
	npm install
	```

3. **Set up your Gemini API key:**
	- Create a `.env` file in the project root.
	- Add:
	  ```
	  VITE_GEMINI_API_KEY=your-gemini-api-key-here
	  ```

4. **Run the development server:**
	```sh
	npm run dev
	```

## Usage

1. Upload your resume (PDF).
2. Enter a job description.
3. Select the type of analysis (ATS Score, Enhancer, Feedback, Keyword Match).
4. Click "Analyze Resume" to receive instant, AI-powered results.

## Tech Stack
- React 19
- Vite
- Tailwind CSS
- pdfjs-dist (for PDF parsing)
- Google Gemini API

## License
This project is licensed under the MIT License.
