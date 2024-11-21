# QuichAI-ChatBot

SmartBot is a state-of-the-art chatbot powered by Gemini AI and built using Streamlit. This application offers advanced natural language understanding to provide insightful, context-aware responses to user queries. A key feature of this project is the ability to export conversations as PDF files, making it ideal for professional sharing or keeping a detailed record of discussions.

## Website's URL

You can explore the deployed chatbot here URL: 
https://quickai-chatbot.streamlit.app/


## Table of Contents

- **Features**
- **Requirements**
- **Installation**
- **Usage**
  
## Features

- **AI-Driven Responses**: Utilizes Gemini AI to deliver accurate, meaningful, and context-aware responses.
- **Interactive Interface**: The chatbot's interface is designed using Streamlit for an intuitive and user-friendly experience.
- **Real-Time Conversations**: Ensures instant and dynamic interaction with users.
- **PDF Export Functionality**: Export entire conversations to PDF for record-keeping or professional use.

## Requirements

- Python 3.6 or higher
- Gemini AI API key
- Streamlit
  
## Installation

```
- Create a virtual environment:
# python -m venv venv
# On Windows use `venv\Scripts\activate

```
- Install the required packages:
```bash
pip install -r requirements.txt
```

- Set up your environment variables:
Create a file named .env in the root directory and add your environment variables:

```bash
GEMINI_API_KEY=your_gemini_api_key
```

## Usage

- Run the Streamlit app:
```
streamlit run chat.py
```    

- Open your browser: Go to http://localhost:8501 to interact with the chatbot.


