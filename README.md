# Business AI Meeting Companion

## Introduction
Consider you're attending a business meeting where all conversations are being captured by an advanced AI application. This application not only transcribes the discussions with high accuracy but also provides a concise summary of the meeting, emphasizing the key points and decisions made.

In our project, we'll use OpenAI's Whisper to transform speech into text. Next, we'll use IBM Watson's AI to summarize and find key points. We'll make an app with Hugging Face Gradio as the user interface.

## Preparing the environment
Let's start with setting up the environment by creating a Python virtual environment and installing the required libraries, using the following commands in the terminal:

1. pip3 install virtualenv 
2. virtualenv my_env # create a virtual environment my_env
3. source my_env/bin/activate # activate my_env

Then, install the required libraries in the environment (this will take time ☕️☕️):

# installing required libraries in my_env
1. pip install transformers==4.35.2 torch==2.1.1 gradio==4.44.0 langchain==0.0.343 ibm_watson_machine_learning==1.0.335 huggingface-hub==0.19.4

Have a cup of coffee, it will take a few minutes.



We need to install ffmpeg to be able to work with audio files in python.

1. sudo apt update

Then run:

1. sudo apt install ffmpeg -y

# Step 2: Creating audio transcription app
Create a new python file speech2text_app.py

# Step 3: Integrating LLM: Using Llama 3 in WatsonX as LLM
Running simple LLM
Let's start by generating text with LLMs. Create a Python file and name it simple_llm.py. You can proceed by clicking the link below or by referencing the accompanying image.

# Step 4: Put them all together
Create a new Python file and call it speech_analyzer.py







