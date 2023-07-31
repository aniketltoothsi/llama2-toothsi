# Llama2-Toothsi-Chatbot
This is a chatbot built using Llama2 and Sentence Transformers.
Uses Langchain and Chainlit. 
Uses Quantized llama-2-7b-model
Runs on decent CPU machine with a minimum of 16GB of RAM.


# steps
1.install dependencies pip -r requirements.txt

2.run ingest.py -> this create your directory that stores your embedding in vector store in this case we are using FAISS db

3.run model.py through chainlit - chainlit provides chat-gpt like UI for any LLM

