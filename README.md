# 🤖 AI-Driven Assignment Evaluation & Scoring System

## 🎯 Problem Statement
Innomatics receives multiple student assignment ZIP files daily, each containing several PDF submissions. Manual evaluation consumes a lot of time and leads to inconsistent scoring.

We aim to build a system that:
- Accepts assignment ZIP files
- Extracts PDFs
- Splits text into Q&A
- Evaluates with an AI model
- Generates detailed scoring reports automatically

---

## 🚀 Workflow

1️⃣ Upload ZIP file of student assignments  
2️⃣ Extract PDFs (supports nested folders)  
3️⃣ Extract text from each PDF  
4️⃣ Split into Question + Answer pairs  
5️⃣ LLM evaluates each answer  
6️⃣ AI returns **Score (0–10)** + **Feedback**  
7️⃣ Final report generated as structured JSON  

---

## 📌 Sample Output (Report)

**Student:** John Doe  
**Module:** Python Basics

| Q.No | Question | Score | Feedback |
|------|----------|-------|----------|
| 1 | What is a list in Python? | 8/10 | Good explanation but missed examples |
| 2 | Write a loop to print 1 to 5 | 10/10 | Correct logic and output |

**Total Score: 90/100**  
**Overall Feedback:** Very good but add more examples next time.

---

## 🌐 Demo

🔗 **Live Demo Link:**  
👉 *https://youtu.be/0YdWo36fqu8*

---

## 🖼 System Snapshots

### Dashboard UI
<img width="1920" height="881" alt="AI-Driven Assignment Evaluation and Scoring System Snapshot" src="https://github.com/user-attachments/assets/3f8da83d-2ea1-41cc-bea7-184ba69d6617" />

---

## ✨ Key Benefits
- Fully automated evaluation
- Faster & fair scoring
- Useful feedback for improvement
- Easily scalable for batch assignments

---

## 🔮 Future Enhancements
- Code execution validation
- Plagiarism check
- Role-based portals for faculty & students
