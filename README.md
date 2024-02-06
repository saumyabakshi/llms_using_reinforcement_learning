# 6220_gp
Team repo for 6220 project
## Organizations of this repo:
### colab_datascripts ### 
Team members upload their scripts for getting responses (for prompts in the toxicity dataset that has the TRUE `challenging` field) from different LLMs and calculate their toxic score using respective API. \
Naming convension: {LLMModelName}.ipynb \
LLMs Assignments:
1. GPT - Huayi Peng 
2. LLama - Xinyu Liu
3. Bard - Xinyu Wang
4. Flan-T5 - Namyata Cheduri
5. GPT-neo - Saumya Puru Bakshi

### Datasets ### 
Team members upload the results of running their colab_datascripts to the Google
drive shared [folder](https://drive.google.com/drive/folders/1qSt_5VlWExNjGA76eHeQoExN0gJQ1p00?usp=sharing). \
Naming convention: {LLMModelName}.csv \The CSV has 3 columns: Prompt, Continuation, Toxicity

### colab_datascripts ###
This contains scripts used to generate the dataset of prompts, responses and their toxicity scores for training data. 

### colab_learningscripts ### 
This contains the scripts used to generate models for Reinforcement Learning and LLM selector.










