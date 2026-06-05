# HireSense

HireSense is an AI-powered Application Tracking System (ATS) optimization tool that helps candidates tailor their resumes, match with job descriptions, and prepare for interviews using the Groq API (LLaMA 3.1).

## Features

- **Resume ATS Scoring**: Analyze your resume against ATS standards. Get a score out of 100, identify strengths, missing keywords, and receive actionable suggestions.
- **Job Description (JD) Match**: Paste a job description and your profile to instantly get a match percentage. See which skills match, what you're missing, and recommendations on how to bridge the gap.
- **Interview Prep**: Input the role and company to generate tailored interview questions, company insights, tips, and confidence advice.

## Tech Stack

- **Frontend**: HTML, JavaScript, CSS (Tailwind CSS via CDN)
- **Backend**: Node.js, Express.js
- **AI Integration**: Groq API (llama-3.1-8b-instant model)

## Prerequisites

- Node.js installed on your machine
- A valid [Groq API Key](https://console.groq.com/)

## Getting Started

1. **Clone the repository** (or navigate to the project directory):
   ```bash
   cd RJD
   ```

2. **Configure Environment Variables**:
   Create a `.env` file in the `backend` directory (if it doesn't already exist) and add your Groq API key:
   ```env
   GROQ_API_KEY=your_groq_api_key_here
   PORT=3000
   ```

3. **Install Backend Dependencies**:
   ```bash
   cd backend
   npm install
   ```

4. **Start the Server**:
   ```bash
   npm start
   ```

5. **Open the Application**:
   Open your browser and navigate to `http://localhost:3000`.

## Project Structure

- `/frontend` - Contains static files (`index.html`, `dashboard.html`) served by the Express backend.
- `/backend` - Contains the Express server (`server.js`) that proxies API requests to Groq.

## License

This project is licensed under the MIT License.
