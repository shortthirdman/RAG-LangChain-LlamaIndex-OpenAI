# RAG using LangChain, LlamaIndex, and OpenAI

Retrieval-Augmented Generation (RAG) using `LangChain`, `LlamaIndex` and `OpenAI`

## Summary

**Large Language Models (LLMs)** can produce incorrect yet plausible responses due to “hallucination,” stemming from outdated knowledge. The **Retrieval-Augmented Generation (RAG)** framework addresses this by integrating an information retrieval system into the LLM pipeline. Instead of relying solely on pre-trained data, RAG enables the model to dynamically fetch accurate, up-to-date information from external sources during response generation. This approach enhances the relevance and accuracy of the information provided without the need for constant retraining or fine-tuning.


## Local Setup

  - Create a Python virtual environment and activate
	
	```shell
	python -m venv <env-name>
	```
	
	```shell
	.\<env-name>\Scripts\activate
	```

  - Install the packages and dependencies as listed in requirements file
	
	```shell
	pip install -r requirements.txt --no-cache-dir --disable-pip-version-check
	```

  - Start your development `Jupyter Notebook` or `Jupyter Lab` server
	
	```shell
	jupyter lab --notebook-dir=.\notebook --no-browser
	```
	
	```shell
	jupyter notebook
	```
	
	```
	jupyter_nbextensions_configurator
	```