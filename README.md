
# CodeGuru

CodeGuru is custom AI based model which generate code based on text input, basically it convert text into different code format i.e (HTML,Python & Java).Write any code with the help of custom prompt.



## Documentation

[Code Llama](https://ai.meta.com/blog/code-llama-large-language-model-coding/)

Code Llama is a state-of-the-art LLM capable of generating code, and natural language about code, from both code and natural language prompts.

Code Llma is released by Meta with four sizes of 7B, 13B, 34B, and 70B parameters respectively. Each of these models is trained with 500B tokens of code and code-related data, apart from 70B, which is trained on 1T tokens. The 7B and 13B base and instruct models have also been trained with fill-in-the-middle (FIM) capability, allowing them to insert code into existing code, meaning they can support tasks like code completion right out of the box.


Gradio - https://www.gradio.app/

Gradio is an open-source Python package that allows you to quickly build a demo or web application for your machine learning model, API, or any arbitrary Python function.



## Features

- Fast and easy in setup
- Present as webpage and share
- Permanently host it on Hugging Face
- Friendly web interface so that anyone can use it, anywhere!


## Installation

Install by using pip command

```bash
  pip install gradio
```
    
## Examples

```javascript
# install package
%pip install -U langchain-ollama


# Create the model in Ollama
ollama create codeguru -f Modelfile

# run the model
ollama run codeguru

# Generate a response
url="http://localhost:11434/api/generate -d"{
    "model" : "codeguru",
    "prompt" : "Who are you?"
}
```

