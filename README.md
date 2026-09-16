# ResumeAI — AI-Powered ATS Resume Analyzer

**ResumeAI** is an intelligent, full-stack Applicant Tracking System (ATS) application designed to help job seekers optimize their resumes for modern automated recruitment pipelines. By leveraging artificial intelligence, the application parses resume contents, evaluates them against specific job descriptions, and provides detailed, actionable insights alongside an objective ATS compatibility score.

## ⚙️ Tech Stack

- **Frontend Framework:** React (Vite)
- **Routing & Architecture:** React Router v7 (with native nested routing)
- **State Management:** Zustand (for high-performance, boilerplate-free global state)
- **Styling & UI:** Tailwind CSS 
- **Type Safety:** TypeScript
- **Cloud Infrastructure & AI:** Puter.js (Client-side cloud framework utilized for serverless authentication, cloud storage, and large language model integration)

## 🔋 Core Architectural Features

- **Serverless Authentication:** Implemented secure user authentication handling directly within the client environment via Puter.js, maintaining user session persistency without a dedicated backend server layer.
- **Secure Cloud Storage:** Built custom resume upload workflows that store user documents securely, mapping file metadata directly to user profiles.
- **AI Matching & Prompt Engineering:** Designed complex prompts using serverless LLM calls (GPT-4 / Claude models via Puter SDK) to execute advanced document OCR, extract skills, and perform matching diagnostics against technical job criteria.
- **Tailored ATS Diagnostics:** Generates granular, contextual feedback breaking down keyword gaps, formatting issues, and precise textual recommendations to maximize resume discovery.
- **Modular Component Design:** Built with a highly reusable, fully responsive UI architecture using modern component layout practices for cross-device compatibility.

## 🤸 Quick Start

Follow these steps to set up and run the project locally on your machine.

### Prerequisites
Make sure you have the following installed on your machine:
- **Node.js** (v18 or higher recommended)
- **npm** or **yarn**

### Installation Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/raspreets23/resume-ats-analyzer.git
   cd resume-ats-analyzer
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Start the Development Server:**
   ```bash
   npm run dev
   ```

4. **Build for Production:**
   ```bash
   npm run build
   ```
