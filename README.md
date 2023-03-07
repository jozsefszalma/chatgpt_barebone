# basic chatgpt api implementation in Python

work in progress!

### set up 
env variables (e.g. in a .env file if using vscode) 
- "KEY", for your openai API key 
- "PROMPT_SYSTEM" (optionally) if you want to give your chatbot a default personality (e.g. helpful expert in area x)

### known issues:
- the UI will only work in Jupyter environments that handle ipywidgets properly (e.g. Databricks' Jupyter does not)
- enter or shift-enter in the input window is captured by vscode, use the Send button instead
- in vscode the default key binding to turn a cell into markdown is "m", you need to re-bind that in the settings as vscode captures it during typing
