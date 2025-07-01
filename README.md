<<<<<<< HEAD

TaskFlow: An Intelligent To-Do List Web App
TaskFlow is a modern, full-stack to-do list application designed to help you stay organized and productive. It features a clean, responsive user interface and is powered by AI to help you prioritize your tasks effectively.

🚀 Project Overview
This project is a To-Do List web application that supports full CRUD (Create, Read, Update, Delete) functionality. It's built with a modern tech stack centered around Next.js and leverages Google's Generative AI for intelligent task prioritization.

✨ Key Features
Add, Edit, and Delete Tasks: Full CRUD operations to manage your to-do list.
Mark as Complete: Easily track your progress by marking tasks as done.
Persistent Storage: Your tasks are saved in your browser's local storage, so you won't lose them.
Responsive UI/UX: A clean, intuitive, and mobile-friendly interface built with Tailwind CSS and ShadCN UI.
AI-Powered Prioritization: A unique feature that uses AI to analyze your tasks and suggest priorities, helping you focus on what matters most.
🛠️ Tech Stack
This project is built using a modern, powerful tech stack:

Framework: Next.js (with App Router)
Language: TypeScript
Styling: Tailwind CSS
UI Components: ShadCN UI
AI Integration: Genkit (with Google Gemini)
State Management: React Hooks (useState, useEffect, useMemo)
Backend Logic: Next.js Server Actions (for AI integration)
While the original request mentioned the MERN stack, this project uses an integrated Next.js architecture, where the frontend and backend logic are colocated. This modern approach simplifies development and deployment while providing excellent performance.

⚙️ Setup and Installation
To get this project up and running on your local machine, follow these simple steps.

Prerequisites
Node.js (v18 or later)
npm or yarn
1. Clone the repository
git clone https://github.com/your-username/taskflow.git
cd taskflow
2. Install dependencies
npm install
3. Set up environment variables
The AI prioritization feature uses the Google Gemini API. You'll need an API key to use it.

Create a .env file in the root of the project by copying the example file:
cp .env.example .env
Get your free API key from Google AI Studio.
Open the .env file and paste your API key:
GOOGLE_API_KEY="YOUR_GOOGLE_API_KEY"
4. Run the development server
npm run dev
The application will be available at http://localhost:9002.

🌐 Deployment
You can deploy this Next.js application to any hosting provider that supports Node.js, such as Vercel, Netlify, or Firebase App Hosting.

Vercel: Your Vercel Deployment Link
Firebase App Hosting: Your Firebase App Hosting Link
Remember to set up your GOOGLE_API_KEY as an environment variable in your hosting provider's settings.

Built with ❤️ for productivity.
taskflow-ai-todo
a9c26f8c934be8ccbb985cf228d82cfd6613fb06
