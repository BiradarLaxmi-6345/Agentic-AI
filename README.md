# Agentic Calculator 🧮

An AI agent-based calculator built as part of my **Agentic AI course**. 
The agent can solve mathematical expressions accurately, including ones 
that require correct order of operations (BODMAS/PEMDAS).

## Project Info

| Field         | Details                          |
|---------------|-----------------------------------|
| **Type**      | AI Agent Project                  |
| **Framework** | smolagents                        |
| **UI**        | Gradio                            |
| **Language**  | Python                            |
| **Status**    | ✅ Completed (Unit 1 project)      |
| **Course**    | Agentic AI Course                 |

## Features
- Performs basic arithmetic: addition, subtraction, multiplication, division
- Correctly handles BODMAS/PEMDAS order of operations
- Built using an AI agent framework, so it reasons through the problem 
  instead of just running a fixed formula
- Simple Gradio-based UI for easy interaction

## Tech Stack
- Python
- [smolagents](https://github.com/huggingface/smolagents)
- Gradio

## How to Run

1. Clone this repository
\```
git clone https://github.com/BiradarLaxmi-6345/Agentic-AI.git
cd Agentic-AI
\```

2. Install dependencies
\```
pip install -r requirements.txt
\```

3. Run the app
\```
python app.py
\```

4. Open the local Gradio link shown in your terminal to use the calculator.

## What I Learned
This project was built while completing Unit 1 of my Agentic AI course. 
I learned how to structure an agent with defined tools and prompts, and 
how to connect it to a simple UI using Gradio.

## Future Improvements
- Add support for more complex math (exponents, roots, trigonometry)
- Improve error handling for invalid expressions
- Add a history feature to see previous calculations
