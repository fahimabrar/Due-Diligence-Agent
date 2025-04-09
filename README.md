# Due-Diligence-Agent

### 1. Install LLM and Embeddings model,

First you need to install Ollama (https://ollama.com/) to your computer. 

Install one Large Language Models from here, 
https://ollama.com/search

For example, to install deepseek-r1 model, from your termial you need to run,
```
ollama run deepseek-r1:1.5b
```
N:B: Select smaller model (e.g. 1 billion parameters) to run it on you CPU.

### 2. Python Libraries
   To install python libraries, you can install one by one manually from requirements.txt

or from terminal, 
```
pip install -r requirements.txt
```

### 3. Run the APP
To run the app, from your terminal. 
```
streamlit run app.py
```
