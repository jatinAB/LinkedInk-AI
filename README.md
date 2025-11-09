# 🪶 LinkedInk-AI

An AI-powered LinkedIn Post Generator that learns your unique writing style from previous posts and helps you create fresh, engaging, and authentic LinkedIn content with just one click.


**LinkedInk-AI** is designed to help users maintain a consistent and engaging LinkedIn presence by generating posts that match their unique writing style.

### How It Works

1. **Upload Past Posts** – Feed your previous LinkedIn posts into the system.
2. **AI Analysis** – The tool analyzes tone, structure, and key topics from your content.
3. **Select Preferences** – Choose a topic, language, and post length.
4. **Generate Post** – The AI creates a new post that mirrors your writing style and personality.
5. **Refine & Publish** – Review, edit if needed, and share directly on LinkedIn.


## 🧠 Technical Workflow
<img src="resources/architecture.jpg" alt="System Architecture"/>

1. **Stage 1:** Collect LinkedIn posts and extract their tone, structure, and content patterns.  
2. **Stage 2:** Generate new posts based on selected topic, tone, and length using few-shot learning from past posts.

---

## ⚙️ Setup Guide

### 1. Get an API Key
- Visit [Groq Console](https://console.groq.com/keys) to create your API key.  
- Add it inside your `.env` file:
```

GROQ_API_KEY=your_api_key_here

````

### 2. Install Dependencies
```bash
pip install -r requirements.txt
````

### 3. Launch the Application

```bash
streamlit run main.py
```

---

## 🧩 Tech Stack

* **Streamlit** – User interface and workflow control
* **Groq API (LLM)** – Core text generation engine
* **Python** – Backend processing and integration
* **Few-shot Learning** – Mimics user’s past writing tone and structure

---

## 🧠 Key Features

* Learns your unique writing style from previous posts
* Generates context-aware, topic-based LinkedIn posts
* Allows customization of tone, topic, and length
* Streamlit-based UI for a clean and interactive experience

---

## 📜 License

This project is licensed under the **MIT License**.
However, **commercial usage** is **strictly prohibited** without written permission from the author.
Attribution is required for any distribution or derivative work.

---

💬 *Built to empower professionals and creators to write smarter, faster, and more consistently with AI.*

```

---

Would you like me to include your **Firebase integration and post history saving** features in this README as well (for the latest version of your app)?
```
