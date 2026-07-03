# AI-Story-Generator

This project is a multi-agent AI Story Generator built with Streamlit, LangGraph, and LangChain that uses Google's gemini-2.5-flash-lite model to automatically write a story and craft a fitting title from a single user prompt. It works by structuring the workflow into a specialized Story Agent and Title Agent managed by a central orchestrator graph to handle the state seamlessly.

To get started:
1) Navigate into the project folder
2) Set up a Python virtual environment
3) Install the required dependencies using pip install -r requirements.txt. 
4) Create a .env file in the root directory containing your GOOGLE_API_KEY=your-key-here
5) Launch the web application locally by running streamlit run app.py 
