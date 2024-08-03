# Meta-Llama-3.1-70B-ColabxGroq-API

Meta Llama 3.1-70B is one of the open source LLM released by meta It is a very capable model with a whopping 70 billion parameters. It supports 8 Languages `English, German, French, Italian, Portuguese, Hindi, Spanish, and Thai`.

Here we are using Groq API to get access to the model and run it. Since all the inference is done through Groq API, you can run this notebook on the basic `CPU Runtime` without any gpu. And honestly its really fast.

NOTE: The first step🥇 is to get your own [Groq-API](https://console.groq.com/keys) from their website. Just click on the link then sign up and create your own API.

The next step is to copy and save your API key in the `colab secretes tab`.<br> Just paste the API Key into the value section and name it `GROQ_API_KEY`.

| |Google Colab|
|:--|:-:|
| 🚀 **Llama 3.1-70B-ColabxGroq** |  [![Open in Colab](https://github.com/73LIX/Meta-Llama-3.1-8BxColab/blob/main/asset/colab_logo.svg)](https://colab.research.google.com/drive/1_B3vedI7H994TIm8w0f82Meguj-TtJt0?usp=sharing)

## The NewUI:
This interface comes with some new feature like: <br>
1. Saving your chat history/content into a json file stored in `content/chats`.<br> 
2. Whenever you start a chat, the application saves a json file and the filename is created with some random texts picked up from your conversation.<br>
3. You have the option to start a new chat or select from existing ones so that you can continue your topic/chat with the model without loosing any previous data or information you fed into it. Its basically like continuing your chat from wherever you left it off.
4. You can also update the list of available chats. This basically means that when you create a new chat by toggling on the `Start New Chat` option, it creates a new `chat_history json file` but it won't be updated in the `Select Chat` dropdown instantly to do that you need to click on the `Update Chat list` button(its like a refresh buttons for your saved chats).<br>

❗Remember to **Untick✅** the `Start new chat` option if you want to continue in the same chat as you are in or **Else** it will keep on creating new chats everytime you prompt something to the model. So if you want to continue in the same chat then untick the `Start new chat`.


## Try out my other notebooks:

| |Google Colab|GitHub|
|:--|:-:|:-:|
| ⭐ **Llama 3.1-8B_Colab** | [![Open in Colab](https://github.com/73LIX/Meta-Llama-3.1-8BxColab/blob/main/asset/colab_logo.svg)](https://colab.research.google.com/drive/10c_GQ8wqVXuX5JciX0gHVstO0WHaUbqD?usp=sharing ) | [![GitHub](https://github.com/73LIX/Meta-Llama-3.1-8BQuantisedxColab-Ollama/blob/main/assets/github.svg)](https://github.com/73LIX/Meta-Llama-3.1-8BxColab.git)
| 🌟 **Llama 3.1-8B_QuantisedxOllama** |  [![Open in Colab](https://github.com/73LIX/Meta-Llama-3.1-8BxColab/blob/main/asset/colab_logo.svg)](https://colab.research.google.com/drive/1S9q6cvH8y2WMml7pczg0Bl-VS6Le-jzZ?usp=sharing) | [![GitHub](https://github.com/73LIX/Meta-Llama-3.1-8BQuantisedxColab-Ollama/blob/main/assets/github.svg)](https://github.com/73LIX/Meta-Llama-3.1-8BQuantisedxColab-Ollama.git)
