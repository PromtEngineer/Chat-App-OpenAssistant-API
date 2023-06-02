# Chat-App-OpenAssistant-API
A quick tutorial on how to interact with Open Assistant API and use it in your own Apps. GUI is based on streamlit. 

![ChatApp](https://github.com/PromtEngineer/Chat-App-OpenAssistant-API/assets/134474669/dbcd36be-55f5-44e6-b3e7-1c1eb110d854)


## Clone the Repo:
Clone the repository. 
```shell
git clone https://github.com/PromtEngineer/Chat-App-OpenAssistant-API.git
```

## Environment Setup
In order to set your environment up to run the code here, first install all requirements:

```shell
pip install -r requirements.txt
```

## OpenAI API Key 

You will need the OpenAI API key to run this, get your HuggingFace key from [here](https://huggingface.co/settings/tokens)
In the `.env` set your API key. 

```shell
HUGGINGFACEHUB_API_TOKEN=
```

## Run the WebApp:

```shell
streamlit run huggingChat.py
```
