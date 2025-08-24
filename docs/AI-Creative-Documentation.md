# AI-Creative: AI-Powered Recipe Generation from Food Images

🔗 [Live Demo](https://aicreative.website)

---

## 🎯 Project Goal

AI-Creative is a web application that allows users to upload images of ingredients or meals, and the system automatically generates personalized recipe suggestions.

This project demonstrates the practical use of AI in image processing and text generation, combining backend, frontend, and machine learning models.

---

## 🛠 Tech Stack

- **Frontend:** React, Vite, Typescript, Tailwind CSS
- **Backend:** Python (Flask), REST API    
- **AI/ML:** Gemini AI / Pollinations.ai to generate images  
- **Deployment:** Render (frontend, backend)  
- **CI/CD:** GitLab

---

## 📈 Features

- Upload images of ingredients or meals 
- Automatic recipe generation (ingredients + step-by-step instructions)  
- User preferences support (e.g., dietery, cuisine type) 
- Live demo available online

---

## 🔍 How It Works (Architecture)

```mermaid
flowchart LR
    A [User uploads food image] --> B [Backend Flask API]
    B --> C [AI Model analyzes image]
    C --> D [AI model extract recognited ingriedients and generates recipe based on them and user preferences]
    D --> E [React Frontend displays recipe to user]
```

## 💡 Highlights

- Full integration of AI + frontend + backend
- Fully working live demo
- Production-ready architecture
- Demonstrates real-world AI application in a web project