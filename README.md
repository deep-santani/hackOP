# hackOP
**A Flask Web-App that puts online the GPT-2 reduced model released by OpenAI**

## The problem hackOP AI solves
hackOP AI is a large transformer-based language model with 1.5 billion parameters, trained on a dataset. We created a new dataset which emphasizes diversity of content, by scraping content from the Internet.hackOP AI allows you to give a sentence , and it will write a context following this sentece with a quite credible speech.

## Challenges we ran into
The Problem is how to make model effcient so for efficiency we use gpt2 model with 1.5 billion parameters which increase the most efficiency of hackOP AI. We have less CPU power so it take more time in execution.

## Technologies we used
(1)TensorFlow   (2)Deep Learning  (3)GPT2-Model

## Adding the Model
The model needs to be placed in a folder called **./models/ Usually the model is the **117M**, that can be downloaded using [the sh script provided in the original OpenAI Github](https://github.com/openai/gpt-2/blob/master/download_model.sh):

## Execution
python server.py
