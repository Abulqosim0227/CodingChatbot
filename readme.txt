### add OPENAI key uisng

export OPENAI_API_KEY= <openai_apikey>

### Replace <openai_apikey> with your API key

### Run the file using the command:
streamlit run coding_assistant_chatbot.py

### If you run into this error: "inotify watch limit reached", use the following command instead:
streamlit run coding_assistant_chatbot.py --server.fileWatcherType none


### You can play around with it using the following prompt:
### "I want to learn pandas in python. Teach me how to get started". Follow the guidelines provided by the chatbot
