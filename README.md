# basic chatgpt api implementation in Python

work in progress!

### Set up 
env variables (e.g. in a .env file if using vscode) 
- "KEY", for your openai API key 
- "PROMPT_SYSTEM" (optionally) if you want to give your chatbot a default personality (e.g. helpful expert in area x)

### Known issues:
- the UI will only work in Jupyter environments that handle ipywidgets properly (e.g. Databricks' Jupyter does not, vscode is marginal)
- if using vscode keep in mind:
  - enter and shift-enter in the input window are captured by vscode, use the Send button instead
  - in vscode the default key binding to turn a cell into markdown is "m", you need to re-bind that in the settings as vscode captures it during typing
