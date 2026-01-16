app.py 🚀

## Welcome! 👋

This is `app.py`, a smart conversational agent, designed to chat with visitors on a website. It answers your questions about Ed's career, skills, background, and much more with the help of advanced AI!

## What Can It Do? 🌟

- Chat with users in natural language using [OpenAI GPT-4o-mini](https://openai.com)
- Pull details from Ed's LinkedIn resume (PDF) to provide accurate info
- Record user contact info and questions for follow-up
- Send instant notifications when someone shows interest (via Pushover)
- Friendly web chat interface powered by Gradio

  <p align="center">
    <img
      src="https://github.com/user-attachments/assets/56b20630-d90a-49f8-b8c7-f1b3b23fa492"
      height = 480px,
      width = 480px>
  </p>

## Getting Started 🛠️

Make sure you have Python 3.8 or higher installed on your computer.

Install the required packages with this command:

```bash
pip install python-dotenv openai requests pypdf gradio
```

## Setup 🧰

1. Create a `.env` file in the project folder and add these lines to set your Pushover credentials:

```
PUSHOVERTOKEN=your_pushover_api_token_here
PUSHOVERUSER=your_pushover_user_key_here
```

2. Make sure the `linkedin.pdf` file (Ed's resume) is in the same folder as `app.py`.

## How to Run 🏃‍♂️

Simply run the script with Python:

```bash
python app.py
```

A chat window will open in your browser where you can start talking with Ed! 🎉

## Configuration Tips ⚙️

- Environment variables are loaded automatically from `.env`.
- Pushover notifications require valid tokens (see setup above).
- If you want to update Ed's LinkedIn info, replace the `linkedin.pdf` file.

## Want to Help? 🤝

Feel free to contribute! You can improve the chat features, add new tools, or enhance the user experience.

