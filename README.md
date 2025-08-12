# 🧠 Prepwise – AI-Driven Mock Interview Platform  
💼 **Your Personal AI Interview Coach**  

Prepwise is a next-generation AI-powered mock interview platform designed to prepare you for real-world job interviews through interactive voice conversations, instant AI feedback, and personalized coaching.  
Built with cutting-edge tech like **Next.js**, **Vapi AI**, and **Google Gemini**, it simulates real interview conditions so you can walk into any interview with absolute confidence.

---

## 🚀 Live Link  
🔗 **[Visit Prepwise](https://prepwise-ecru.vercel.app/)**  

*Note: Initial load may take a few seconds due to free hosting.*

---

## 🔋 Key Features  

- 🗣 **AI Voice Interviews** – Realistic mock interviews with Vapi AI Voice Agents  
- 🧠 **Smart AI Feedback** – Instant, detailed performance insights via Google Gemini  
- 🔐 **Secure Authentication** – Powered by Firebase Auth  
- 📊 **Performance Dashboard** – Review transcripts and track progress over time  
- 🎨 **Modern UI/UX** – Tailwind CSS + shadcn/ui for sleek, responsive design  
- 📱 **Fully Responsive** – Works seamlessly on desktop, tablet, and mobile  
- 🏗 **Scalable Architecture** – Modular, reusable components for easy maintenance  

---

## 🛠 Tech Stack  

- **Next.js 15** (App Router, TypeScript)  
- **Tailwind CSS + shadcn/ui**  
- **Firebase** (Authentication, Firestore, Storage)  
- **Vapi AI** (Voice Agents)  
- **Google Gemini AI** (Feedback & Analysis)  

---

## 📂 Project Structure  

```bash
prepwise/
├── app/                          # Next.js App Router
│   ├── (auth)/                   # Auth pages (Sign-in, Sign-up)
│   │   ├── sign-in/page.tsx
│   │   └── sign-up/page.tsx
│   ├── (root)/                   # Core pages (Home, Interview, Feedback)
│   │   ├── interview/[id]/feedback/page.tsx
│   │   └── interview/[id]/page.tsx
│   ├── globals.css               # Global styles
│   └── layout.tsx                 # Root layout
│
├── components/                   # Reusable UI & custom components
│   ├── ui/                       # UI components (button, form, input, etc.)
│   ├── Agent.tsx
│   ├── AuthForm.tsx
│   ├── InterviewCard.tsx
│
├── constants/                    # Static config values
├── firebase/                     # Firebase client & admin config
├── lib/                          # Server actions & utilities
├── public/                       # Static assets (logos, icons, covers)
├── types/                        # TypeScript type definitions
├── package.json                  # Dependencies & scripts
├── tsconfig.json                 # TypeScript config
└── README.md                     # Documentation
```
---
## ⚙ Setup Instructions
### 1️⃣ Install Dependencies
```
npm install
```
### 2️⃣ Configure Environment Variables
Create a ``.env.local`` file in the root directory and add:
```
NEXT_PUBLIC_VAPI_WEB_TOKEN=your_vapi_web_token
NEXT_PUBLIC_VAPI_WORKFLOW_ID=your_vapi_workflow_id

GOOGLE_GENERATIVE_AI_API_KEY=your_google_gemini_api_key
NEXT_PUBLIC_BASE_URL=http://localhost:3000

NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_firebase_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_firebase_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_firebase_app_id

FIREBASE_PROJECT_ID=your_firebase_project_id
FIREBASE_CLIENT_EMAIL=your_firebase_client_email
FIREBASE_PRIVATE_KEY=your_firebase_private_key

```
Replace the placeholders with your actual credentials.
---
### 3️⃣ Run the Development Server
Visit: ```http://localhost:3000```

---
## 👨‍💻 Author
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/sudhir-singh-840603250/)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-black)](https://github.com/SudhirSingh62)

