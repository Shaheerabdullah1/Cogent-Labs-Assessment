# Cogent-lab-Assessment
Welcome to the Cogent Labs Assessment Repository, This repository is dedicated to the submission of assessment tasks assigned by Cogent Labs.
Task # 1
Crime and Punishment Book Summarization
This project focuses on summarizing the book "Crime and Punishment" by Fyodor Dostoevsky using various Python libraries including NLTK, LangChain, and OpenAI's GPT model(gpt-3.5-turbo). The process involves extracting text from a PDF, preprocessing it, splitting it into manageable chunks, and generating summaries.

Project Modules
1.Text Preprocessing: Clean and preprocess the extracted text to make it suitable for summarization.
2.Text Extraction: Extract text from the PDF file of "Crime and Punishment" using document loaders from langchain.
3.Text Splitting: Split the preprocessed documents into smaller chunks for efficient processing.
4.Summarization: Use a language model (LLM) to generate summaries for each chunk of text.

Requirements
Python 3.12
NLTK
OpenAI
FPDF
python-dotenv
LangChain v0.2 

Execution Process
1. Clone the repository:
git clone https://github.com/Shaheerabdullah1/Cogent-Labs-Assessment.git
cd crime-and-punishment-summarization

Install the Requirements
pip install -r requirements.txt

Download the NLTK punkt package
import nltk
nltk.download('punkt')

Usage
1.Place the PDF file of "Crime and Punishment" in the project directory.
2.Update the file_path variable in the notebook to the location of your PDF file.
3.Run the Jupyter notebook to execute the summarization process.

TASK # 2
Personalized Study Plan Creator
This project focuses on creating personalized study plans for students using LangChain. The AI assistant analyzes student information, including subjects, learning styles, extracurricular activities, personal goals, and challenges, to generate tailored study plans that promote academic excellence and personal development.

Requirements
Python 3.12
LangChain v0.2 

Install the Requirements
pip install -r requirements.txt

Execution Process
1. Clone the repository:
git clone https://github.com/Shaheerabdullah1/Cogent-Labs-Assessment.git
1.Template Definition: Define a template for the AI to follow when generating personalized study plans.
2.Input Data: Provide detailed student information to the AI assistant.
3.Personalized Study Plan Generation: Use the template and input data to generate a comprehensive and holistic study plan for each student.
4.Provide detailed student information
5.Run the Jupyter Notebook











