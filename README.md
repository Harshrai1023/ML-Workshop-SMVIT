# Google Gemini-Pro Chat Interface

## Overview

This Python code provides a simple Streamlit interface for interacting with Google Gemini-Pro, a generative AI chat model. Users can have a conversation with the Gemini-Pro model, and the chat history is displayed along with the conversation input box.

## Prerequisites

Before running the code, make sure to set up the required dependencies:

- **Streamlit:** The user interface is built using Streamlit, a popular Python library for creating web applications with minimal code.
- **Google Gemini-Pro API:** To use the Gemini-Pro model, you need to obtain an API key from [Here](https://makersuite.google.com/app/apikey) and configure it using the `GOOGLE_GEMINI_KEY` environment variable.
- **dotenv:** The `dotenv` library is used for loading environment variables from a file.

## Installation

1. Install the required Python packages using the following command:

    ```bash
    pip install streamlit google-generativeai python-dotenv
    ```

2. Create a `.env` file in the project directory and add your Google Gemini-Pro API key:

    ```env
    GOOGLE_GEMINI_KEY=your_api_key_here
    ```

## Usage

Run the Python script, and it will start a Streamlit web application with the Gemini-Pro chat interface.

```bash
streamlit run app.py
```

Open your web browser and navigate to the provided URL to begin chatting with Google Gemini-Pro.

## Code Structure

- The Gemini-Pro API is configured using the provided API key.
- A Streamlit session state is used to maintain the chat history.
- The chat history is displayed above the current input box.
- User messages are sent to the Gemini-Pro model, and the assistant's responses are displayed.

Feel free to customize the code according to your needs or extend its functionality.

## Note

Ensure that you use the Gemini-Pro API responsibly and comply with any terms of service provided by Google for using their generative AI models.
