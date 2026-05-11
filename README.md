# Mini ChatGPT

A small ChatGPT-style chatbot project built around OpenAI's chat completions API.

The main Python entrypoint is [2_chatgpt.py](2_chatgpt.py), which starts a simple terminal chatbot. The repository also includes a lightweight browser chat UI in [index.html](index.html), [script.js](script.js), [script2.js](script2.js), and [style.css](style.css).

## Features

- Interactive command-line chatbot
- Uses OpenAI chat completions
- Keeps the conversation history in memory during the session
- Includes a separate front-end chatbot interface

## Requirements

- Python 3.8 or newer
- An OpenAI API key
- Internet access for API requests

## Setup

1. Install the OpenAI Python package:

   ```bash
   pip install openai
   ```

2. Open [2_chatgpt.py](2_chatgpt.py) and set your API key before running the script.

3. Save the file.

## Run the chatbot

```bash
python 2_chatgpt.py
```

When the program starts, it first asks what type of chatbot you want to create. After that, type your messages and press Enter to chat.

## Notes

- Stop the program with `Ctrl+C`.
- For safer sharing and deployment, store the API key in an environment variable instead of hardcoding it in the source file.
- The browser UI files are separate from the Python script and can be opened directly in a browser.

## Project Structure

- [2_chatgpt.py](2_chatgpt.py) - Python chatbot script
- [index.html](index.html) - Front-end chatbot markup
- [script.js](script.js) - Front-end chatbot behavior
- [script2.js](script2.js) - Alternate front-end chatbot script
- [style.css](style.css) - Front-end chatbot styles