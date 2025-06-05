# Vision & Voice AI assistant 

An advanced AI assistant that processes both audio and video inputs to provide interactive responses, utilizing LLMs
like LLama3.1 using groq api, gemini-1.5-flash. 

We Optimized LangChain-based inference pipeline with message history management, enabling accurate voice command recognition
and dynamic interactions, even in noisy environments.


We need an `OPENAI_API_KEY` and a `GOOGLE_API_KEY` to run this code. And then we have to store them in a `.env` file in the root directory of the project.




Create a virtual environment with conda or usual python, update pip, and install the required packages:

Virtual Environment Using pip

```
$ python3 -m venv .venv
$ source .venv/bin/activate
$ pip install -U pip
$ pip install -r requirements.txt
```

Virtual Environment Using conda

```
$ conda create -n venv python=3.11
$ conda activate venv
$ pip install -r requirements.txt
```


Run the assistant:

```
$ python assistant.py
```
