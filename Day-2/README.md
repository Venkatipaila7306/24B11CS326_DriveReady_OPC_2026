# Day 2 – Prompts, Memory and Python Agents

## Project: College Library Assistant

### Overview
This project is a simple AI-powered College Library Assistant developed using Python and the Groq API. It helps students get information about books available in the college library, including book availability and author details.

This task demonstrates important concepts of prompt engineering, conversation memory, JSON handling, Python functions, decorators, and error handling.

### Technologies Used
- Python
- Google Colab
- Groq API
- Groq Python SDK
- JSON

### Concepts Covered

1. **Messages and Roles:** Understanding system and user messages in AI conversations.
2. **System Prompts:** Defining the assistant's role, facts, rules, and response format.
3. **Few-Shot Prompting:** Providing examples to guide the AI in generating appropriate responses.
4. **JSON Output and Parsing:** Extracting structured information from AI responses using JSON.
5. **Conversation Memory:** Maintaining conversation history so the assistant can remember earlier messages.
6. **Python Dictionaries:** Storing book names, authors, and availability details.
7. **Functions and Type Hints:** Creating reusable Python functions with clear input and output types.
8. **Decorators:** Using a decorator to log function calls.
9. **Error Handling:** Handling API errors and JSON parsing errors using `try` and `except`.

### Features
- Answers questions about available books.
- Provides book author information.
- Maintains conversation history.
- Remembers details shared earlier in the conversation.
- Uses structured JSON responses for book-related requests.
- Handles common API and parsing errors.

### How to Run
1. Open the `agenticAI_Day2.ipynb` notebook in Google Colab.
2. Install the required Groq Python package.
3. Add your Groq API key to Colab Secrets with the name `GROQ_API_KEY`.
4. Run the notebook cells sequentially.
5. Ask questions about books available in the library.

### Sample Questions
- Do you have Python books?
- Who is the author of Java?
- Do you have C programming books?
- What is my name?
- Do you have a DBMS book?

### Learning Outcome
Through this task, I learned how to build a simple conversational AI assistant using Python and Groq. I also understood how prompts, few-shot examples, JSON, conversation memory, decorators, and error handling work together in a basic AI application.

---

**Task:** Day 2 – Agentic AI Learning  
**Project:** College Library Assistant
