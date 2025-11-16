# IBM AI Chatbot Web Application  
A Flask-based AI chatbot web application integrating a pretrained NLP model using Hugging Face Transformers.  
This project was built as part of the **IBM AI Developer Professional Certificate Lab: Integrating a Chatbot Into a Web Application**.

---

## 🏷️ Badges

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Flask](https://img.shields.io/badge/Flask-Web_Framework-green)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![HTML](https://img.shields.io/badge/Frontend-HTML-orange)
![JavaScript](https://img.shields.io/badge/Frontend-JavaScript-blueviolet)
![NLP](https://img.shields.io/badge/AI-NLP_Model-red)
![Git](https://img.shields.io/badge/Version_Control-Git-black)
![Course](https://img.shields.io/badge/IBM-AI_Developers_Program-lightgrey)

---

## 📌 Project Objective

The goal of this lab project was to create an interactive **AI-powered chatbot** that accepts user input from a web page, sends it to a server-side NLP model, generates a meaningful response, and displays the reply dynamically in the browser.

This demonstrates skills in **full-stack AI application development**, combining **machine learning**, **web technology**, and **API communication**.

---

## 🧠 Features

- Interactive chatbot UI (HTML, CSS & JavaScript)
- Flask backend with REST API endpoint
- Response generation via Hugging Face Transformers
- Clean, modular, and scalable architecture
- Ready for model upgrades or fine-tuning
- Suitable for deployment (Docker-compatible)

---

## 🏗️ Architecture

```text
+-----------------+         +-----------------------+         +---------------------+
|  Web Frontend   |  <----> |    Flask Application  |  <----> |  HuggingFace Model  |
| (HTML/CSS/JS)   |   AJAX  | (app.py - API Route)  |   NLP   |  Seq2Seq Generation |
+-----------------+         +-----------------------+         +---------------------+