# Day 4 – ABC College Library Assistant

## Project Overview

The ABC College Library Assistant is a simple AI-powered assistant built using Python, LangChain and the Groq API.

It helps students:
- Get book details.
- Check book availability.
- Submit library book requests.
- Extract structured information from student messages.
- Save library requests automatically to Google Sheets.

The project demonstrates how AI agents use tools to perform tasks instead of only generating text responses.

## Technologies Used

- Python
- Google Colab
- Groq API
- LangChain
- Pydantic
- Google Sheets
- gspread

## Features

### 1. Custom Tools

Two tools are created using LangChain's `@tool` decorator:

- `get_book_details(title)` – retrieves book information.
- `check_availability(title)` – checks whether a book is available.

### 2. Structured Output

Pydantic is used to define a `LibraryRequest` data model.

It extracts structured information such as:
- Student name
- Book title
- Request type
- Preferred date
- Additional notes

Five sample student messages are tested to check information extraction.

### 3. Google Sheets Integration

A Google Sheet named **ABC College Library Requests** is used to store student requests.

The `log_library_request()` tool validates the request and saves it as a new row.

### 4. AI Agent

A LangChain agent is created using the Groq language model and the custom library tools.

The agent selects the appropriate tool based on the student's question.

### 5. Tool Testing and Execution Trace

The project also includes:
- Testing a tool with a vague name and docstring.
- Comparing tool selection with clear and unclear descriptions.
- Using `pretty_print()` to inspect agent execution.
- Counting model calls and tool calls.

## Sample Book Catalogue

The project uses a sample library catalogue containing:

- Python Crash Course
- Let Us C
- Clean Code
- Data Structures and Algorithms
- Operating System Concepts

## How to Run

1. Open the Google Colab notebook.
2. Add your Groq API key to Colab Secrets using the name `GROQ_API_KEY`.
3. Run the installation cell.
4. Run the remaining notebook cells in order.
5. Authenticate your Google account when prompted.
6. Open the generated Google Sheet to view saved library requests.

## API Configuration

This project uses the Groq API through LangChain's `ChatGroq`.

The API key is accessed securely through Google Colab Secrets. It is not included in the notebook or repository.

## Learning Outcomes

Through this project, I learned:

- How to create custom tools using LangChain.
- How AI agents select and execute tools.
- How to use Pydantic for structured data extraction.
- How to integrate Google Sheets with Python.
- How to save validated records automatically.
- How to inspect and understand agent execution traces.

## Future Improvements

- Connect the assistant to a real library database.
- Add more books and categories.
- Implement book issue and return tracking.
- Add student authentication.
- Integrate a RAG-based library knowledge assistant.

---

**Project:** Day 4 – Tools, Structured Output and Google Sheets  
**Case Study:** ABC College Library Assistant  
**LLM Provider:** Groq
