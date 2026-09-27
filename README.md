# 🧞 PortfolioGenie

**An AI-Powered Developer Portfolio Compiler & Static Exporter**

🎓 Graduation Project — Digital Egypt Pioneers Initiative (DEPI), Front-End 
React Track — Ministry of Communications & IT

## 📋 Overview

PortfolioGenie is a client-side web application that helps developers build 
a professional portfolio website in under 5 minutes. Users simply input 
their GitHub username, and the app automatically fetches their public 
repositories, language statistics, and bio details.

It features a visual workspace with a split-screen layout — editable forms 
on the left, and a live preview canvas on the right — plus support for 
custom experience and education timelines.

## 💡 The Problem We Solved

- Junior developers waste hours writing boilerplate CSS for portfolio sites 
  instead of building features.
- Static PDF resumes fail to showcase interactive layouts or real projects.
- Backend/database hosting setups are complex and costly for job seekers.

**Our solution:** A serverless, database-free compiler that runs entirely 
client-side — guaranteeing user privacy with zero hosting costs.

## ⚙️ How It Works

1. **Fetch:** User enters their GitHub username → the app calls the GitHub 
   REST API to retrieve profile data, repositories, and language stats.
2. **Customize:** User refines their portfolio across 3 dashboard tabs 
   (Profile, Projects, Timeline) with a real-time live preview.
3. **Export:** A compiler engine bundles everything into a single, 
   standalone HTML file — fully portable, works offline, and can be hosted 
   free on GitHub Pages.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **React 18** | Component composition & state management |
| **React Router** | Page transitions (Landing → Builder) |
| **Framer Motion** | Micro-animations & smooth transitions |
| **Vanilla CSS Modules** | Design tokens & layout system |
| **GitHub REST API** | Fetching profile & repository data |
| **LocalStorage API** | Auto-save session data |
| **FileReader API** | Client-side avatar image processing |
| **Vite** | Build tooling & Hot Module Replacement |

## 🏗️ Architecture

Built as a fully client-side **MVC pattern**:
- **View:** Form editors + Live Preview Canvas
- **Controller:** React hooks, reducers, and Context API
- **Model:** Structured JSON schema synced to LocalStorage and exported to HTML

## 🚀 Roadmap

- Integrate real LLM API (Gemini) for AI-powered copywriting
- Add multiple design themes (dark mode, grid/timeline variants)
- Automated CI/CD deployment to GitHub Pages & Netlify

---
🎓 Graduation Project — DEPI Front-End React Track
