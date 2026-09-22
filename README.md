
# 🎓 LangChain Student Assistant

An AI-powered Student Assistant built using **LangChain, Groq, SQLite, Python, and Pandas**.

This project demonstrates how an LLM agent can dynamically select and use multiple tools to answer student-related questions.

## 🚀 Features

The agent has 4 custom tools:

1. **Get Student Info**
   - Retrieves the student's name and department using their student ID.

2. **Get Student Marks**
   - Retrieves marks for Python, Database, AI, and Web.

3. **Calculator**
   - Calculates total marks and average marks.

4. **Get Passing Rules**
   - Provides the minimum average and minimum marks required to pass.

## 🛠️ Technologies Used

- Python
- LangChain
- Groq LLM
- SQLite
- Pandas

## 🤖 How It Works

The user asks a question in natural language.

The LangChain agent decides which tool is required and calls the appropriate tool.

For example:

```text
User:
What are the marks of student 22CS045?

Agent:
→ get_student_marks()
→ Returns the student's marks
