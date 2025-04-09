# Due-Diligence-Agent

What this app will do, 
- It will search relevant webpages (using duckduckgo api) based on your query.
- Scrape the webpage and add relevant information to a vector database.
- You can select newly created knowledge to provide LLM to generate the response.

What is unique here, 
- Traditional LLM has knowledge cutoff (limited by training data)
- This approach enhance knowledge based on real time data.
- This is locally hosted LLM (so no one gets your data)
- You have more control about the knowledge source (e.g. selecting best knowledge source)

Here is a quick demo (click on the image to see the video demo), 
[![Youtube Demo](https://raw.githubusercontent.com/fahimabrar/Due-Diligence-Agent/refs/heads/main/Screenshot%20from%202025-04-09%2013-27-42.png)](https://www.youtube.com/watch?v=5YVAtmZamtg)

### 1. Install LLM and Embeddings model,

First you need to install Ollama (https://ollama.com/) to your computer. 

Install one Large Language Models from here, 
https://ollama.com/search

For example, to install deepseek-r1 model, from your termial you need to run,
```
ollama run deepseek-r1:1.5b
```

Once downloaded, you can chat directly in the terminal. But if you want to exit from the conversation enter, 
```
/bye
```

to see the downloaded models list, 
```
ollama list
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
