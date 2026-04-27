# chatbot_experiments
ENGLISH: this project is a group of experimentations about chatbots.  

FRANCAIS: ce projet est une série d'expérimentations sur les chatbots.

## Details

Find here a series of Jupyter notebooks describing chatbots in specific contexts.
The contexts are inspired by projects suggested by the [Lang Chain Academy](https://academy.langchain.com/).
I'm taking their courses but the notebooks produced are not copies of solution from the Lang Chain Academy.

## Installation 

Jupyter notebooks are written in Python. In order to execute them, you need to check several requirements.

### Prerequisites

- Python (>=3.12, <3.14)
- Package manager **pip**

### Installation steps


Copy the text file *example.env* into a file named *.env*

```bash
cp example.env .env
```

Create a virtual environment and download the packages required

```bash
python -m venv .venv
source .venv/bin/activate 
pip install -r requirements.txt
```

## *.env* file 

The *.env* file contains keys to access model (LLM) providers or services.
It is important because the dotenv module enables a notebook to read key-value pairs from the *.env* file and to set them in the notebook's environment. Below, there are links to create one's own keys.

- LLM: get an OpenAI API Key [here](https://openai.com/index/openai-api/)
- LLM-friendly web search engine: get a Tavily key [here](https://app.tavily.com/home)

Once created, place the keys in the *.env* file 

Important: keys are secret 





