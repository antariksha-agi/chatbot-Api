# chatbot-Api

A beginner backend project built using FastAPI and SQLite.

## Features

* Store user messages
* Generate bot replies
* Save chat history
* Store timestamps
* Retrieve previous chats
* Delete chat records
*  AI model integration
*  Smarter bot responses
*  chat memory limitet to 10 chats
*  Deployed to ngrok

## Technologies Used

* Python
* FastAPI
* SQLite
* Pydantic
* groq API
* llm model llama3
* uvicorn

## Project Workflow

User Message 
   ↓
Pydantic Model (Message Type Selection) 
   ↓
API Route 
   ↓
Wanted Query Selection 
   ↓
LLM → Process 
   ↓
Insert into SQLite Database 
   ↓
Response


## Future Improvements

* User authentication
* Search chat history


## Learning Goals

This project was built to learn backend development, APIs, databases, and system design fundamentals.

