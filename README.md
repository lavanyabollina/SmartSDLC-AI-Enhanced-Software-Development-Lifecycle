
# 💡 SmartSDLC: AI-Enhanced Software Development Lifecycle
SmartSDLC is a next-gen AI assistant designed to optimize and automate various phases of the Software Development Lifecycle (SDLC). Built using Streamlit and powered by IBM Watsonx’s Granite LLM models, this application supports developers and product teams through intelligent modules tailored to real-world development needs.

## 🚀 Core Modules & Functionality
**📥 Requirement Upload & Classification**

  Upload PDF documents containing software requirements. 

 Automatically extract and categorize content based on SDLC phases.

Transform raw inputs into structured User Stories.

AI Code Generator

Convert plain language instructions into executable Python code.

Bug Fixer

Detect and automatically fix bugs in provided code snippets.

Test Case Generator

Generate unit tests (using unittest or pytest) from your code or user stories.

Code Summarizer

Receive concise explanations and overviews of given code blocks.

Chat Assistant

Engage with an SDLC-savvy chatbot for questions, suggestions, or programming help.

## 🛠️ Technology Stack
Layer	Tools/Frameworks
Frontend	Streamlit
AI Backend	IBM Watsonx.ai + Granite LLMs
PDF Parsing	PyMuPDF (fitz)
Language	Python 3.12+

## 🔐 IBM Watsonx Integration
To configure the app for IBM Watsonx:


api_key = "<YOUR_API_KEY>"


project_id = "<YOUR_PROJECT_ID>"


base_url = "https://<your-region>.ml.cloud.ibm.com"


model_id = "ibm/granite-3-3-8b-instruct"


Replace the placeholders with your actual IBM Cloud credentials and endpoint details to enable AI functionality.

