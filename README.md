# 🧑‍💻 AI Interview App  

An AI-powered platform for conducting seamless and proctored online interviews, making recruitment smarter and faster. Leverage Gemini AI for question generation and advanced features like voice-to-text transcription, all while maintaining high data security. 🚀

---
![Next.js](https://img.shields.io/badge/Next.js-12.0.0-blue.svg)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14.0-green.svg)
![Gemini AI](https://img.shields.io/badge/Gemini%20AI-Integrated-orange.svg)
![Clerk Authentication](https://img.shields.io/badge/Authentication-Clerk-brightgreen.svg)

<div align="center">
  <img height="800" width="400" src="https://github.com/Raryan-23/AI-interview-app/blob/main/AI-Interview-2024-12-10-120849.png"  />
</div>

## Project Overview

This repository contains the code for an **AI-powered Interview App** designed to assist both candidates and recruiters by automating the interview process. The application leverages advanced technologies such as AI-generated questions, voice-to-text conversion, proctoring, and secure authentication. It provides a seamless experience for both candidates taking interviews and recruiters reviewing responses.

The app is built with **Next.js**, **React**, **TailwindCSS**, **Gemini AI**, and **Clerk** for authentication. The backend uses **Neon** with **PostgreSQL** for scalable data storage and **Shadcn** and **HyperUI** for a clean, modern UI.

This project demonstrates how cutting-edge technologies can streamline the hiring process and enhance both the candidate and recruiter experience.

## Technologies Used

This project uses the following technologies:

- **Next.js**: A React-based framework used for building the frontend and server-side logic.
- **React**: A JavaScript library for building user interfaces.
- **TailwindCSS**: A utility-first CSS framework to build custom designs quickly.
- **Gemini AI**: Utilized to generate dynamic and intelligent interview questions.
- **Clerk**: Provides authentication and user management, including multi-factor authentication.
- **Shadcn & HyperUI**: Libraries for modern UI components, enhancing the user interface.
- **Neon**: A serverless platform that integrates with PostgreSQL for scalable data storage.
- **PostgreSQL**: Relational database used to store interview responses and user data securely.

### Backend & Database
The backend is powered by **Neon** (serverless PostgreSQL), providing a scalable, cloud-based solution for managing interview data. This ensures high performance even with large amounts of data. Responses are stored securely in the database, with the integration of voice-to-text technology.

### Frontend & UI
The frontend is designed using **Next.js**, **React**, and **TailwindCSS**, providing a responsive and dynamic interface. **Shadcn** and **HyperUI** enhance the user experience with modern components and beautiful UI design.

### Security & Authentication
We use **Clerk** for user authentication, ensuring secure login and session management. It also supports multi-factor authentication (MFA) for enhanced security.


## 🌟 Features  

- **AI-Driven Interviewing**: Uses Gemini AI to dynamically generate interview questions.  
- **Proctored Environment**: Ensures fairness with always-on camera and microphone.  
- **Voice-to-Text Transcription**: Candidate responses are automatically transcribed and stored in the database.  
- **Secure Authentication**: Integrated with Clerk for a robust and seamless sign-in experience.  
- **Modern UI Components**: Built with ShadCN and HyperUI for an intuitive and responsive interface.  
- **Scalable Backend**: Powered by Neon Drizzle ORM with PostgreSQL for secure and efficient data handling.  

---

## 🛠️ Tech Stack  

| **Category**          | **Technology**          |  
|------------------------|-------------------------|  
| **Frontend**          | Next.js, ShadCN, HyperUI |  
| **Authentication**    | Clerk                  |  
| **Backend**           | Neon Drizzle ORM       |  
| **Database**          | PostgreSQL             |  
| **AI**                | Gemini AI              |  

---
## How It Works

### 1. Candidate Login
The candidate logs in using **Clerk** for secure authentication. After logging in, the candidate is ready to begin the interview process.

### 2. AI-Generated Questions
Once authenticated, **Gemini AI** generates a set of interview questions that adapt based on the role or skills required. These questions are presented to the candidate one by one.

### 3. Proctored Interview
The candidate’s camera and microphone are turned on during the interview to ensure a proctored environment. This prevents cheating and ensures the interview process is fair.

### 4. Recording and Storing Responses
The candidate’s responses are recorded and stored in the database. The voice answers are converted to text using **voice-to-text** technology, making it easy for recruiters to analyze.

### 5. Reviewing Responses
Recruiters can review the candidate's responses in real-time, or at their convenience. The stored text responses make it easier for recruiters to analyze the answers quickly.

### 6. Finalizing the Interview
Once the interview is completed, the recruiter can send feedback to the candidate and decide if another round of interviews is necessary. The process is logged and stored in the database for future reference.

## Project Setup and Installation

To get the project up and running locally, follow these steps:

### Prerequisites

- **Node.js** (v14 or above)
- **npm** (or Yarn, pnpm, bun)
- **Git** for version control
- **PostgreSQL** installed or access to a PostgreSQL database instance (or use Neon's cloud offering).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-powered-lms.git


## 📚 Getting Started  

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).  

### Prerequisites  

- [Node.js](https://nodejs.org/en/)  
- [PostgreSQL](https://www.postgresql.org/)  

### 🚀 Development  

Run the development server:  

```bash  
npm run dev  
# or  
yarn dev  
# or  
pnpm dev  
# or  
bun dev  
