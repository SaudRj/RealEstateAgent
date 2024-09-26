# HomeMatch Application

## Overview
The HomeMatch application is a personalized real estate agent that utilizes a Large Language Model (LLM) to generate real estate listings and match them with user preferences.

## Features
- Generate diverse and realistic real estate listings.
- Store listings in a vector database for efficient search.
- Semantic search based on user preferences.
- Personalized listing descriptions tailored to user needs.

## How to run the Code:
1- Clone the repository:
git clone <repository-url>
cd <repository-directory>

2- Install the dependencies:
pip install -r requirements.txt

## Dependencies (requirements.txt)
Before running the application, ensure you have the following installed , You can install the required libraries using pip:
langchain=0.0.305
openai=0.28.1
pydantic>=1.10.12
pytest>=7.4.0
sentence-transformers>=2.2.0
transformers>=4.31.0
chromadb==0.4.12
jupyter==1.0.0
tiktoken==0.4.0

Additional dependencies:
pip install sentence_transformers
!pip install sentence-transformers
!pip install huggingface-hub
pip install --upgrade sentence-transformers huggingface-hub

Note: After installing these libraries, you may need to restart the kernel for the changes to take effect.