# ⚖️ LegalMate-AI

**LegalMate-AI** is an advanced AI-powered platform that simplifies and enhances the way users interact with legal documents.  
It allows users to **upload**, **summarize**, and even **chat with their legal documents**, making legal information more accessible, understandable, and actionable.

## 🧠 Overview

LegalMate-AI bridges the gap between legal complexity and user understanding.  
By integrating **Mistral 7B Instruct**, it delivers fast, context-aware summaries and intelligent answers drawn directly from user-uploaded documents.  
The system uses **Firebase Authentication** for secure user management and **MongoDB** for storing documents, summaries, and chat history.

## 🚀 Key Features

- 📄 **Document Upload & Analysis**  
  Users can upload documents in supported formats (PDF or DOCX) for AI-based processing.

- 🧩 **AI-Powered Summarization**  
  Generates concise and meaningful summaries of lengthy legal documents using **Mistral 7B Instruct API**.

- 💬 **Chat About This Document**  
  Enables interactive Q&A with the uploaded document — users can ask questions, clarify terms, and get contextual legal insights.

- 🔒 **Secure Authentication**  
  Uses **Firebase Authentication** for safe and seamless login and user management.

- ☁️ **Persistent Storage**  
  Stores user documents, summaries, and chat histories securely in **MongoDB**.


## 🏗️ Tech Stack

| Layer | Technology Used |
|-------|------------------|
| **Frontend** | React.js |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **Authentication** | Firebase Authentication |
| **AI Model** | Mistral 7B Instruct API |
| **Storage** | MongoDB (for chats & documents) |


## 🔁 Workflow

1. User logs in securely via **Firebase Authentication**.  
2. Uploads a legal document (PDF or DOCX).  
3. The document is processed and stored in **MongoDB**.  
4. The **Mistral 7B Instruct API** generates a summarized version of the document.  
5. The user can interact with the **“Chat About This Document”** feature to ask context-based questions.  
6. All chat history and document details are saved and can be revisited later.

## 🖼️ Screenshots

> Add the following screenshots (recommended size: 900–1200px width).  
> You can place them inside a `/screenshots` folder in your repository.

### 🏠 Home Page
<img width="1908" height="819" alt="Screenshot 2025-11-05 152927" src="https://github.com/user-attachments/assets/00785b79-4ad7-4894-831e-27ce1ae0c049" />

### 🔐 Sign In Page
<img width="1831" height="789" alt="Screenshot 2025-11-05 151959" src="https://github.com/user-attachments/assets/b678d399-a19e-4047-ac63-e2bca3214d1f" />

### 💬 Chat Interface
<img width="1586" height="756" alt="Screenshot 2025-11-05 151655" src="https://github.com/user-attachments/assets/1ba62f8a-cb93-4a38-8d71-b8300f2db7e3" />
<img width="1024" height="649" alt="Screenshot 2025-11-05 151717" src="https://github.com/user-attachments/assets/8524dd0a-3d92-4ca0-8425-f83b1a2529cf" />

### 🧾 Generated Summary Page
<img width="1893" height="813" alt="Screenshot 2025-11-05 151620" src="https://github.com/user-attachments/assets/d268fa0a-0009-4406-b067-bf7fe630ac69" />
