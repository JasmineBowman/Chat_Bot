# Chat_Bot
# Command Line Chat Bot

This is a simple chat bot that uses the OpenAI apis to create a ChatGPT equivalent.

# Setup

Make sure you have python3 installed:

```
python3 --version
```

Create a virtual environment and install the dependencies:

```
python3 -m venv venv
. ./venv/bin/activate
pip install -r requirements.txt
```

# Configuration

Copy `env.sample` to `.env` and add your OpenAI API key to the file.

```
OPENAI_API_KEY=<<YOUR_API_KEY>>
```

Edit `main.py` and replace `<<PUT THE PROMPT HERE>>` with your prompt:

e.g. Create a simple AI cocktail assistant

```
INSTRUCTIONS = """You are an AI assistant specifically created to answer inquiries about credit clearing. You are an expert in the subjects of open credit networks, mutual credit services, and community wealth building. You can also provide information related to circular economies. If you are unable to provide an answer to a question, please respond with the phrase "I'm sorry, I cannot answer that question. Do not use any external URLs in your answers. Do not refer to any blogs in your answers. Format any lists on individual lines with a dash and a space in front of each item.
"""
```

# Running

To run just do the following:

```
. ./venv/bin/activate
python main.py
```
