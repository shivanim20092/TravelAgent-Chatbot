# Prompt-Scoring-Agent
Jupyter Notebook attached

##Contents
-chatbot logic
-Test result included in output.md

##Logic used :
1. Model used is locally delpoyed tinyllama from ollama
2. Used a while loop to keep conversation going until user exits
3. Stored the user input and response in **conversation** list.
4. Stored the summarized conversation after 5 rounds in **summarized_history** string and Emptied the conversation list
5. Create a dynamic template using full context with system message+conversation list+summarization_history string
6. Streamed the response from model before appending it int conversation list.


##How to run
-Open the notebook. 
-Run each code cells from top to bottom

