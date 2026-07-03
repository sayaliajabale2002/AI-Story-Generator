# AI-Story-Generator

This project is a multi-agent AI Story Generator built with Streamlit, LangGraph, and LangChain that uses Google's gemini-2.5-flash-lite model to automatically write a story and craft a fitting title from a single user prompt. It works by structuring the workflow into a specialized Story Agent and Title Agent managed by a central orchestrator graph to handle the state seamlessly.

To get started:
Navigate into the project folder
Set up a Python virtual environment
Install the required dependencies using pip install -r requirements.txt. 
Create a .env file in the root directory containing your GOOGLE_API_KEY=your-key-here
Launch the web application locally by running streamlit run app.py 
