
# PDF-Chatbot
 
 ## clone this repository using the url
 git clone git@github.com:Shreelakshmi2102/PDF-chatbot.git

 ## create the virtual environment in the project folder

 ### cd project PDF-chatbot
 ### run below command to create the virtual environment
 python -m venv pdf-chatbot-venv
 ### activate the venv
 pdf-chatbot-venv/Scripts/activate

## install all the dependencies
pip install -r requirements.txt

## assign groq api key env file
visit this website to create api key 
[visit website](https://console.groq.com/keys)

## install ollama
[ollama website](https://ollama.com/download)
run the executable file of the ollama

## download the embedding model from terminal
ollama pull nomic-embed-text

# run the project  
chainlit run app.py





