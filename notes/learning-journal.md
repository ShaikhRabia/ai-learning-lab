# AI Learning Journal


## Session 001 — 2026-07-27

### What I accomplished
- Set up Google Colab for AI development.
- Installed and tested LiteLLM.
- Connected Python to the Gemini API.
- Created my first program that accepts user input and sends it to an LLM.
- Successfully generated a Python function using Gemini.

### What I learned
- `input()` stores user input in a variable.
- LiteLLM provides a common interface for communicating with different LLMs.
- The `messages` list maintains conversation context.
- System prompts strongly influence the model's behavior.
- The model's response is stored and can be reused in later prompts.

### Challenges I solved
- Switched from the course's OpenAI example to Gemini.
- Configured a working `GOOGLE_API_KEY`.
- Tried different Gemini model names until I found one that worked.
- Fixed a variable naming issue after renaming `what_to_help_with` to `function_request`.
- Discovered that the original system prompt ("turn on the stove and dance") completely changed the model's response.

### Next session
- Extract the Python code from the model's response.
- Continue building the multi-prompt workflow.
