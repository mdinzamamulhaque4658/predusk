# predusk
This is the assignment I created for Predusk internship as an assesment
# This is the link of the google collab file I created  which is linked to the Hugging face space where I deployed my portfolio. You just have to open the hugging face link and my portfolio will be deployed using gradio.
MY GOOGLE COLLAB LINK
https://colab.research.google.com/drive/1NvC6RlqIIv0INnThn9MaCd6cYslwjEjZ?usp=sharing
MY PORTFOLIO LINK IN HUGGING FACE
https://huggingface.co/spaces/behappy092/space
# PLEASE NOT THAT IT WAS TOO DIFFICULT FOR ME TO FINE TUNE MY LLM SINCE I DONT HAVE GOOD GPU SO I COULDNT FINE TUNE IT IN A BETTER WAY. MY COMPUTER WAS GOING TO TAKE 72 HOURS TO FINE TUNE MY LLM WHICH WAS BEYOND THE TIMING WHICH I GOT.
STEPS:
Open my portfolio link
A hugging face space will open
Click on Generate
There will be two pages 
Click on AI chat bot to run my llm ( Please notice that its a bit out of tune because of my previous mentioned reason)










---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------








# 🚀 AI Resume Chatbot & Portfolio

This project is a **personal portfolio website** with an **AI-powered chatbot** that analyzes resumes. It is deployed on **Hugging Face Spaces** and fine-tuned using the **TinyLlama model**.

🔗 **Live Demo:** [Portfolio & Chatbot](https://huggingface.co/spaces/behappy092/space)  
📂 **Google Colab Notebook:** [Training & Fine-Tuning](your-google-colab-link)  

---

## 📌 Features
✅ **Personal Portfolio** – Showcasing skills, projects, and resume  
✅ **AI Chatbot** – Uses an open-source LLM to answer resume-related queries  
✅ **Fine-tuned TinyLlama model** for chatbot responses  
✅ **Deployed on Hugging Face Spaces**  
✅ **GitHub & CI/CD Integration** for smooth updates  

---

## 🚀 How to Run This Project Locally

1️⃣ **Clone the Repository**
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

3️⃣ **Run the Gradio App**
```bash
python app.py
```

4️⃣ **Open the Browser and Test**  
Once the server starts, go to the displayed `localhost` URL in your browser to access the portfolio & chatbot.

---

## 📜 Training & Fine-Tuning Process
1. **Trained the TinyLlama model** using `datasets` and `transformers`.
2. **Created a custom dataset (train.jsonl)** with resume-related queries.
3. **Fine-tuned the chatbot** using the `Trainer` API in Hugging Face.
4. **Saved and pushed the fine-tuned model** to Hugging Face using `HfApi`.
5. **Deployed the app** using `Gradio` on Hugging Face Spaces.

---

## 🚀 Deployment Steps on Hugging Face Spaces
1. **Create a new Space** on Hugging Face with `Gradio` as the SDK.
2. **Clone the Space repository** and add the necessary files (`app.py`, `requirements.txt`).
3. **Push the updates to Hugging Face Spaces**:
```bash
git add .
git commit -m "Updated chatbot and portfolio"
git push
```
4. **Wait for the Space to build & deploy** automatically.

---

## 📬 Contact Me
💼 [LinkedIn](https://www.linkedin.com/in/md-inzamamul-haque-48839930b)  
🐙 [GitHub](https://github.com/mdinzamamulhaque4658)  
📩 Email: 220090008@iitdh.ac.in  

---

### ✅ Final Step
After everything is deployed, **submit the GitHub & Hugging Face Space links** as required! 🚀
