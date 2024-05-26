This is a chatbot made from Ollama Mistral model using langchain 

There are three steps through which you can use this:


Step 1:

Download the Ollama from the official website:

```
https://ollama.com/
```

Step 2:

Download the mistral model using the following command in your terminal:

```
ollama pull mistral
```

You can check the list of model in Ollama using ```ollama list``` command in your terminal. It shows the model name with its size of the model. The mistral model is around of 4.1 GB.

Step 3:

Clone the repository

Step 4:

Install the required libraries using the following command

```
pip install -r requirements.txt
```

Step 5:

Run the following using the following streamlit command:

```
streamlit run app.py
```
