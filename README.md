# voice-assistent
The objective of the project is to interact with a local LLM model by voice. For this purpose, it is proposed to make use of other *speech-to-text* and *text-to-speech* models, being the basic implementation that is sought to be carried out. On this basis we will seek to implement strategies, such as *RAG* to add maximum value to the interaction that we make with our model and our documents.


## Create the environment

To create an environment and install all dependencies we will use [Poetry](https://python-poetry.org/).
It is a tool for dependency management and packaging in Python.
To learn more about the project and how it works you should visit the link.

```bash
poetry install
```

* Note: If you don't have it installed, the first step is to install it following the steps suggested in the project site according to the operating system you have. In Ubuntu it would be:
    ```bash
    pip install poetry
    ```
    To create an environment in the same folder of our project, it is necessary to add a setting

    ```bash
    poetry config vitualenvs.in-project true
    ```
    and now we are ready to create the environment.

## Others dependencies

* To execute the LLM locally we will use [Ollama](https://ollama.com/). If you don't have it installed, follow the steps suggested in the project site.


## Download the models

### LLM model

To download the *Mistral LLM* we just need to run this command line:
```bash
ollama run mistral
```
There are many others models to play and enjoy, it's just an example.

### Speech-to-text model

A possible model for a first test could be use [OpenAI Whisper model](https://github.com/openai/whisper).

### Text-to-speech model

blabla

## Download data

### Audio
https://commonvoice.mozilla.org/en/datasets
