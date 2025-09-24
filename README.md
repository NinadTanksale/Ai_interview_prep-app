# 🤖 AI-Powered Interview Prep App

A smart, full-stack web application built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js) and integrated with the **Gemini API** to help users prepare for technical interviews with personalized AI-generated questions and answers.

---

## 🚀 Key Features

1. **🔐 User Authentication**  
   Secure login & signup using JWT-based authentication.

2. **🎯 Role-Based Interview Sessions**  
   Generate tailored questions based on job role and experience.

3. **🧠 AI-Powered Q&A**  
   Leverage Gemini API to generate high-quality, technical questions and answers.

4. **📚 Accordion Learning UI**  
   View content in an expandable format for a clean study flow.

5. **🧩 Dynamic AI Explanations**  
   Ask AI for explanations to understand tricky concepts.

6. **📌 Pin Important Questions**  
   Save questions to revisit later.

7. **🗃 MongoDB Storage**  
   Persist user sessions and questions securely for future review.

8. **🎨 Clean Tailwind UI**  
   Responsive, accessible, and modern UI with smooth UX.

---

## 📁 Folder Structure Overview
```
AI-Interview-Prep/
├── Backend/
│ ├── config/
│ │ └── db.js
│ ├── controllers/
│ │ ├── aiController.js
│ │ ├── authController.js
│ │ ├── questionController.js
│ │ └── sessionController.js
│ ├── middlewares/
│ │ ├── authMiddlewares.js
│ │ └── uploadMiddlewares.js
│ ├── models/
│ │ ├── Question.js
│ │ ├── Session.js
│ │ └── User.js
│ ├── routes/
│ │ ├── authRoutes.js
│ │ ├── questionRoutes.js
│ │ └── sessionRoutes.js
│ ├── utils/
│ ├── server.js
│ ├── package.json
│ └── package-lock.json
│
├── Frontend/
│ ├── src/
│ │ ├── assets/
│ │ ├── components/
│ │ │ ├── Cards/
│ │ │ ├── Inputs/
│ │ │ ├── Loader/
│ │ │ ├── layouts/
│ │ │ └── DeleteAlertContent.jsx, Drawer.jsx, Modal.jsx
│ │ ├── context/
│ │ │ └── userContext.jsx
│ │ ├── pages/
│ │ │ ├── Auth/
│ │ │ ├── Home/
│ │ │ └── InterviewPrep/
│ │ ├── utils/
│ │ ├── App.jsx
│ │ ├── main.jsx
│ │ ├── index.css
│ │ └── index.html
│ ├── package.json
│ └── vite.config.js
```


---

## ⚙️ Tech Stack

| Layer      | Technology                     |
|------------|--------------------------------|
| Frontend   | React.js, Tailwind CSS, Vite   |
| Backend    | Node.js, Express.js            |
| Database   | MongoDB                        |
| AI Service | Gemini API (Q&A + Explanation) |
| Auth       | JWT, Passport.js (if used)     |

---

## 🛠 Setup Instructions

### 📌Backend Setup

```bash
cd Backend
npm install
```

### Create a `.env` file in the root of Backend:

```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
```

### Start the backend server:

```bash
node server.js
```

---

## 💻Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```
- Access the app at: http://localhost:5173
- Make sure the backend is running at http://localhost:5000 or update the API base URL accordingly in `axiosInstance.js`.

---

## 📍 Example Workflow
- Sign up or log in.
- Select a job role and experience level.
- Receive a curated list of questions.
- View answers and AI explanations on demand.
- Pin important Q&As for future review.

---

## For Contributing
If you want to contribute to this project, please follow these steps:
- `Fork` the repository.
- Create a new branch `(git checkout -b feature/your-feature-name)`.
- Make your changes and commit them `(git commit -m 'Add some feature')`.
- Push to the branch `(git push origin feature/your-feature-name)`.
- Open a pull request.

---

## Project Maintainer
**Github:** [Swedeshna Mishra](https://github.com/SwedeshnaMishra)
