# 🇯🇵 LLM-Powered Japanese Conversational Bot

## 💡 Project Overview

This is a full-stack, AI-driven language practice application designed to improve proficiency in various Japanese speech styles (linguistic registers). The application provides a unique conversational partner that can switch between extreme formality, casualness, historical dialogue, and specific personality-driven speech, providing **real-time English critique** on the user's input.

This project demonstrates strong capabilities in secure API handling, Full-Stack architecture (MERN stack concepts), and advanced prompt engineering.

---

## ✨ Core Features

| Feature | Description | Skill Demonstrated |
| :--- | :--- | :--- |
| **Multi-Style AI Engine** | Instantaneously switches the AI's persona and linguistic register (speech style) using dynamic prompt loading. | Advanced Node.js, Dynamic Imports, Prompt Engineering. |
| **Linguistic Personas** | Four complex personas for diverse practice scenarios (see below). | Nuanced LLM Instruction, Persona Modeling. |
| **Real-Time Critique** | Every AI response includes a separate, mandated English critique of the user's immediately preceding message. | Structured LLM Output, Response Parsing. |
| **Secure Full-Stack Design** | Frontend (React) communicates only with the backend (Node/Express), ensuring the API key remains securely stored on the server side. | Security Best Practices, API Development. |

---

## 👤 Available Conversational Styles

This bot offers four distinct styles for highly specific linguistic practice:

| Style | Persona | Key Linguistic Focus |
| :--- | :--- | :--- |
| **Keigo (敬語)** | **Shibusawa-san:** A formal, senior colleague. | High-level politeness, complex honorifics (sonkeigo, kenjōgo). |
| **Tameguchi (タメ口)** | **Āmin:** A casual, familiar friend. | Conversational slang, contractions, and relaxed grammar. |
| **Samurai (侍語・武士言葉)** | **Muramasa (浪人):** A proud Rōnin retainer to a Sengoku Warlord. | Archaic grammar, Bushi Kotoba, stern and dignified tone. |
| **Onee (オネエ口調)** | **Machiko Duplex:** A sharp, street-smart figure with deep compassion. | Distinctive Onee speech patterns, wit, and strong personality. |

---

## 🛠️ Technology Stack

* **Frontend:** React (JavaScript, CSS)
* **Backend:** Node.js, Express.js
* **Database (Placeholder):** MongoDB (or potential for integration)
* **AI Model:** Google Gemini API

## 🚀 Setup and Installation

Follow these steps to run the project locally.

### Prerequisites

* Node.js (v18+) and npm/yarn installed.
* A Gemini API Key (obtained from Google AI Studio).

### 1. Clone the Repository

```bash
git clone [YOUR REPO URL HERE]
cd LLM-Powered-Japanese-Conversational-Bot
