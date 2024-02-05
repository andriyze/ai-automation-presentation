# AI-Automation Presentation

## GPT

### ai-automation repo

[ai-automation](https://github.com/andriyze/ai-automation)

`pbpaste | python3 security.py`


### OpenAI API key

Get your [OpenAI key](https://platform.openai.com/api-keys)

`export OPENAI_API_KEY=sk-...`


### Python3

Get yourself  [Python3](https://www.python.org/downloads/)


### Fabric

Daniel Miessler's [Fabric](https://github.com/danielmiessler/fabric)



## Local LLMs

### Ollama

[ollama](https://ollama.ai/download)

`curl https://ollama.ai/install.sh | sh`

`ollama serve`

`ollama run dolphin-mixtral:8x7b-v2.7-q5_K_M`

`ollama run codellama:7b-code`

### Ollama Web UI

`docker run -d --network=host -v ollama-webui:/app/backend/data -e OLLAMA_API_BASE_URL=http://127.0.0.1:11434/api --name ollama-webui --restart always ghcr.io/ollama-webui/ollama-webui:main`


### Uncensored Dolphin Mixtral model

https://huggingface.co/cognitivecomputations/dolphin-2.7-mixtral-8x7b

https://erichartford.com/dolphin-25-mixtral-8x7b



### Open Interpreter

Must have Python installed

[Open Interpreter](https://github.com/KillianLucas/open-interpreter)

`pip install open-interpreter`


### Local copilot

[cody.dev](https://sourcegraph.com/cody )

[twinny](https://github.com/rjmacarthy/twinny)


### LM Studio

https://lmstudio.ai/


### GPT4All

https://gpt4all.io/index.html