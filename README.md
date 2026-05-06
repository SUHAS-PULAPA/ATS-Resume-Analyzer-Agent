# 🚀 AI ATS Resume Analyzer (n8n Workflow)

An AI-powered Resume Analyzer that evaluates resumes for ATS compatibility using workflow automation, Telegram bot integration, and AI-based analysis.

---

## 📌 Overview

This project automates the process of resume evaluation by integrating a messaging interface, an automation engine, and an AI model.

Users submit resumes via a Telegram bot, and the system:
- Extracts resume content  
- Analyzes it using AI  
- Generates an ATS score  
- Provides actionable feedback  

The system is designed for real-time usage with minimal manual intervention.

---

## 🧠 Features

- ⚡ Real-time resume analysis  
- 🤖 AI-powered evaluation  
- 📲 Telegram bot integration  
- 📧 Email-based report delivery  
- 🔄 Fully automated workflow  
- 🧩 Modular and scalable design  

---

## 🏗️ System Architecture
User (Telegram)
→ Input Processing & Validation
→ Resume Extraction
→ AI Analysis (Gemini)
→ Result Formatting
→ Output Delivery (Telegram + Email)

---

## ⚙️ Workflow Description

1. **Telegram Trigger**
   - Receives resume from user

2. **Validation**
   - Ensures correct file/input format

3. **Data Processing**
   - Extracts and prepares resume content

4. **AI Analysis**
   - Evaluates resume based on:
     - Structure  
     - Keywords  
     - Skills  
     - Content quality  

5. **Result Formatting**
   - Converts output into readable format

6. **Output Delivery**
   - Sends results via Telegram and Email

---

## 📊 Sample Output

- **Resume Score:** 78/100  
- **Overall Quality:** Good  

**Strengths:**
- Well-structured sections  
- Proper contact information  

**Suggestions:**
- Improve keyword optimization  
- Add measurable achievements  

---

## 🧪 Tech Stack

- **Workflow Automation:** n8n  
- **Messaging Platform:** Telegram Bot API  
- **AI Model:** Google Gemini  
- **Email Service:** Gmail API  
- **Scripting:** JavaScript  

---

## 📈 Results

- Successfully automated resume analysis  
- Real-time processing achieved  
- AI-generated meaningful insights  
- Multi-channel output delivery  

---

## ⚠️ Limitations

- No job description matching  
- General evaluation (not role-specific)  
- Output depends on AI prompt quality  

---

## 🔮 Future Improvements

- Job description-based matching  
- Resume ranking system  
- Web dashboard for visualization  
- AI-based resume rewriting  
- Multi-language support  

---

## 🚀 How to Run

1. Set up n8n workflow  
2. Configure:
   - Telegram Bot API  
   - Gemini API  
   - Gmail API  
3. Activate workflow  
4. Send resume via Telegram  

---

## 💡 Use Cases

- Students improving resumes  
- Job seekers preparing for ATS systems  
- Recruiters for quick screening  

---

## 📜 License

This project is for educational purposes only.

---

## 🙌 Acknowledgment

This project demonstrates the integration of AI and workflow automation to solve real-world problems efficiently.
