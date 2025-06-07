# 🧠 AI-Powered Blog Application

Welcome to my AI-Powered Blog Application — a modern full-stack blogging platform where users can create, read, update, and delete blog posts with the assistance of AI. This application integrates Google Gemini for smart content generation and ImageKit for efficient media handling, while offering a secure, responsive, and intuitive user experience.

---

## 🚀 Features

- ✨ **AI-Generated Content**: Boost creativity using Google Gemini to generate blog titles, summaries, and ideas.
- 🔐 **Secure Authentication**: JWT-based user login and registration system.
- 📝 **Rich Text Editing**: Feature-rich blog editor powered by Quill.js for formatting and media embedding.
- 🗂️ **Persistent Blog Storage**: Blogs are stored in MongoDB and can be accessed or edited anytime.
- 📱 **Responsive UI**: Clean, modern design using Tailwind CSS, optimized for all screen sizes.
- 🛠️ **Admin Access**: Admin can manage blogs and control access.
- 🖼️ **Image Uploads**: Seamless media hosting via ImageKit for fast and optimized image delivery.

---

## 🛠 Tech Stack

- **Frontend**: React.js, Vite, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas
- **Authentication**: JWT
- **AI Integration**: Google Gemini API
- **Rich Text Editor**: Quill.js
- **Image Handling**: ImageKit.io
- **Deployment**: Vercel (Frontend & Backend)

---

## 🔧 How It Works

### 🛡️ User Roles & Access

- **Admin Access**: Only the admin has login credentials.
  - Can **create**, **edit**, and **delete** blog posts.
  - Has access to AI features and image uploads.
- **Public Access**: All other users (visitors) can:
  - **View** blog posts.
  - **Comment** on them without authentication.

---

### 🧑‍💼 Admin Login & Session Handling

- Admin logs in using email and password.
- On successful login:
  - A **JWT token** is issued and securely stored in local/session storage.
  - This token is used to authorize requests to protected routes.

---

### ✍️ Blog Creation & Editing (Admin Only)

- Admin writes blog content using a **Quill.js rich text editor**.
- AI assistance (via **Google Gemini API**) helps generate:
  - Blog titles
  - Content paragraphs
  - Summaries
- Blog posts are stored in **MongoDB** and updated in real time.

---

### 🧠 AI Integration with Google Gemini

- Admin can request AI-generated content with a single click.
- Prompts are sent to **Google Gemini**, and the response is:
  - Injected directly into the blog editor.
- This enhances productivity and creativity in writing.

---



