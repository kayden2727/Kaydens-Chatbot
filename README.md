# Kayden's Chatbot
This is Kayden's Chatbot, a simple question-answering chatbot powered by the Hugging Face Transformers library.
Users can ask the bot questions to learn more about Kayden, including his hobbies, major, school and more. The user can also refer to the context or data_set for ideas of questions. 
The chatbot is using a pre-trained NLP model to understand and respond to user questions.

## Website Link
chatbot-4a6d5.web.app

## Prerequisites

To run this chatbot, ensure you have Python 3.7 or higher installed.

You can install all required libraries using the provided requirements file:

```bash
pip install -r requirements.txt
```

## How to Run Locally

1. **Start the Backend Server:**
   Open a terminal in the project directory and run:
   ```bash
   python chatbot_script.py
   ```
   This will start the Flask server on `http://127.0.0.1:5000`.

2. **Run the Frontend:**
   Open `public/index.html` in your browser.
   *Recommended:* Use the "Live Server" extension in VS Code to serve the file (usually at `http://127.0.0.1:5500`).

3. **Start Chatting:**
   Type your questions in the input box and press Enter!

## Features
 - Answers questions about Kayden, such as:
    - His name, age, and major.
    - His hobbies, job, and school.
    - Contact information and social media links.
- Built using a question-answering model from Hugging Face.
- Accessible via a web interface

Feel free to contribute or suggest improvements!
