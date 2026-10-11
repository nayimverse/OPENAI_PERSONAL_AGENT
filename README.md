# AI Personal Assistant

A small Flask web app that uses the OpenAI API to answer questions and summarize email text.

## Requirements

- Python 3.10 or newer
- An OpenAI API key

## Setup

1. Create and activate a virtual environment:

   ```powershell
   py -m venv .venv
   .venv\Scripts\Activate.ps1
   ```

2. Install the dependencies:

   ```powershell
   pip install Flask python-dotenv openai
   ```

3. Create a `.env` file in the project root and add your API key:

   ```dotenv
   OPENAI_API_KEY=your_api_key_here
   ```

   `.env` is excluded from Git; do not commit API keys or other secrets.

## Run

```powershell
python main.py
```

Then open http://127.0.0.1:5000 in your browser.
