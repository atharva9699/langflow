# MCQ quiz LANGFLOW
<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/f2641028-fed2-4135-a6e6-d87dcaa520b0" />

Easily create **auto-generated multiple-choice quizzes (MCQs)** for any topic using a no-code/low-code GenAI flow built in **LangFlow**.

---

## 🎯 Project Goal
Build a GenAI pipeline that:
- Accepts a topic  and the number of questions  
- Generates a validated multiple-choice quiz with an answer key and clear rationales  

---

## ✨ Key Features
- Topic-driven quiz generation for MCQs only  
- Adjustable difficulty levels 
- Configurable question count  

---

## 🛠️ Architecture (Flow Overview)
**Input → Astra DB → Parser → Prompt Template → LLM → Output**

### Components in LangFlow
- **Input:** topic & number of questions  
- **Astra DB:** store/retrieve context  
- **Parser:** enforce schema & structure  
- **Prompt Template:** combine system + user instructions  
- **LLM:** Groq  
- **Output:** display formatted quiz  

---

## 💻 Tech Stack
- **LangFlow** – visual orchestration UI  
- **Astra DB** – database for context & storage  
- **Groq LLM** – for quiz generation  
- **Python 3.12.1**

---

## 📝 Sample Output

 
**User:** Create 10 quiz questions on *Agentic AI*  
**AI:** gemma2-9b-it  

> ### Agentic AI Quiz  
> *(Choose the best answer for each question)*

1. What is the key difference between traditional AI and agentic AI?  
   a) Traditional AI is faster than agentic AI  
   b) Traditional AI focuses on predictions, while agentic AI takes actions to achieve goals  
   c) Traditional AI requires human intervention, while agentic AI operates independently  
   d) Traditional AI is more complex than agentic AI  

2. Which of the following is NOT a core principle of agentic AI?  
   a) Perception  
   b) Learning  
   c) Reasoning & Planning  
   d) Action & Adaptation  

3. What does *perception* mean in agentic AI?  
   a) Understanding and responding to human emotions  
   b) Sensing and interpreting data from the environment  
   c) Learning from past experiences  
   d) Making decisions based on logical reasoning  

4. How is agentic AI different from a simple rule-based program?  
   a) It can learn and adapt based on feedback  
   b) It is faster than rule-based programs  
   c) It can access real-time data  
   d) It is more complex to develop  

5. What impact can agentic AI have on industries?  
   a) Increased productivity and innovation  
   b) Reduced need for human workers  
   c) Higher risk of job displacement  
   d) **All of the above**

6. A key concern in deploying agentic AI is:  
   a) High development cost  
   b) Potential for unintended consequences  
   c) Lack of public awareness  
   d) Integration difficulty  

7. What role do knowledge graphs play in agentic AI?  
   a) Enhance reasoning abilities  
   b) Enable multi-agent collaboration  
   c) Learn from unstructured data  
   d) **All of the above**

8. What are *autonomous enterprises* in agentic AI?  
   a) Fully human-free businesses  
   b) Businesses using agentic AI to self-optimize and self-correct  
   c) Firms relying solely on AI for decisions  
   d) Fully automated organizations  

9. Why is governance important for agentic AI?  
   a) Ensure accountability and responsible use  
   b) Prevent malicious misuse  
   c) Protect privacy and data security  
   d) **All of the above**

10. A potential benefit of agentic AI is:  
    a) Improved efficiency and productivity  
    b) Enhanced decision-making  
    c) Handling complex, dynamic environments  
    d) **All of the above**

**Answer Key:**  
1-b, 2-b, 3-b, 4-a, 5-d, 6-b, 7-d, 8-b, 9-d, 10-d
<img width="1440" height="900" alt="Screenshot 2025-09-20 at 12 54 03 AM" src="https://github.com/user-attachments/assets/f9f8b256-4b4d-455d-8e30-a3ae4307cfd6" />

<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/79b3eb48-3aaf-428e-991e-92a0fd767631" />
