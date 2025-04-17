📧 Cold Email Generator with LLMs (Jupyter Notebook Based)

This project allows you to craft personalized cold emails using a Large Language Model (LLM) with optional job description scraping. It is fully contained within a Jupyter Notebook for quick prototyping—no UI or hosting required.

🚀 Key Features

🔮 Leverages LLMs (Groq + LLaMA 3) for intelligent and tailored email generation

🌐 (Optional) Web scraping support to extract job or company-related data

🧠 Customizable prompts for varying tone and messaging style

📁 Entirely Jupyter Notebook-based — no need to deploy or create a frontend

📎 (Optional) Portfolio matching using ChromaDB and a CSV file of your past projects

🛠️ Installation

Install all necessary dependencies with:

pip install langchain langchain-community langchain-groq chromadb pandas

📁 Project Files

email_generator.ipynb # Main notebook for running the tool
my_portfolio.csv # (Optional) Project portfolio CSV file
README.md # Documentation

📌 Workflow

Set up the LLM with Groq and LLaMA 3.

(Optional) Scrape job or company web pages using WebBaseLoader.

(Optional) Parse out job details like required skills or roles.

(Optional) Use ChromaDB to match your past projects (from a CSV).

Generate a cold email tailored to the job opportunity.

View the output right in the notebook.

📄 Email Prompt Sample

Write a short and persuasive cold email introducing our product to the company.
Use the job description context and include links to relevant work.

📎 Portfolio CSV Format (Optional)

If using the optional project matching, structure your CSV like this:

Techstack,Links
"Python, NLP, LLMs",https://example.com/project1
"React, TypeScript",https://example.com/project2

📌 Notes

This tool runs entirely in a notebook — no frontend or server is needed.

You'll need a valid Groq API key to access the LLM.

Markdown cells are included to guide you through the steps.
