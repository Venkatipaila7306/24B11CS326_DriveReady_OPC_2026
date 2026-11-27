# Day 3 – LangChain, Conversation Memory and AI Agents

## Project: Sweet Crumbs Home Bakery Assistant

### Overview

This project is a simple AI-powered Home Bakery Assistant developed using Python, LangChain, and the Groq API. It helps customers get information about bakery products, including prices, eggless options, and order requirements.

This task demonstrates important concepts of LangChain, prompt templates, conversation memory, output parsing, Python functions, CSV handling, automated testing, and AI agents.

### Technologies Used

- Python
- Google Colab
- Groq API
- LangChain
- LangChain Groq
- CSV

### Concepts Covered

1. **LangChain Integration:** Connecting the Groq language model using LangChain.
2. **Chat Models:** Using `ChatGroq` to interact with the Groq language model.
3. **Prompt Templates:** Creating structured prompts using `ChatPromptTemplate`.
4. **Conversation Memory:** Maintaining conversation history using `MessagesPlaceholder`.
5. **Output Parsing:** Converting AI responses into plain text using `StrOutputParser`.
6. **LCEL Chains:** Connecting prompts, language models, and output parsers using the pipe operator.
7. **Python Functions:** Creating reusable functions with type hints.
8. **CSV Handling:** Creating and reading test cases using Python's CSV module.
9. **Automated Testing:** Testing AI responses using predefined questions and expected keywords.
10. **AI Agents:** Creating a basic LangChain agent using `create_agent`.

### Features

- Answers questions about bakery products and prices.
- Provides information about eggless cake options.
- Calculates order totals.
- Maintains conversation history.
- Remembers customer details shared earlier in the conversation.
- Supports English and Telugu responses.
- Handles unknown queries by referring customers to the owner.
- Tests responses using predefined test cases.

### How to Run

1. Open the `agenticAI_Day3.ipynb` notebook in Google Colab.
2. Install the required packages.
3. Add your Groq API key to Colab Secrets with the name `GROQ_API_KEY`.
4. Run the notebook cells sequentially.
5. Ask questions about bakery products and services.

### Sample Questions

- Do you have eggless chocolate cake?
- How much is the plum cake?
- Can you deliver to my home in 2 hours?
- Do you make cupcakes?
- How much for 3 cupcakes and a chocolate cake?
- ఏగ్ లెస్ కేకులు ఉన్నాయా?
- What is my name?
- What ingredients do you use in your frosting?
- Do you make custom birthday cakes?

### Learning Outcome

Through this task, I learned how to build a conversational AI assistant using Python, LangChain, and Groq. I also understood how prompt templates, conversation memory, output parsing, LCEL chains, CSV handling, automated testing, and AI agents work together in a basic AI application.

---

**Task:** Day 3 – Agentic AI Learning  
**Project:** Sweet Crumbs Home Bakery Assistant
