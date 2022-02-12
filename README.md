# Quora Question Pairs (NLP Project)

### Can you identify question pairs that have the same intent?

Where else but Quora can a physicist help a chef with a math problem and get cooking tips in return? Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

Currently, Quora uses a Random Forest model to identify duplicate questions. In this competition, Kagglers are challenged to tackle this natural language processing problem by applying advanced techniques to classify whether question pairs are duplicates or not. Doing so will make it easier to find high quality answers to questions resulting in an improved experience for Quora writers, seekers, and readers.

# About this project:
A NLP project to find weather given 2 questions are same are not semantically speaking.

# demo:
![image](https://user-images.githubusercontent.com/68845761/153724208-029178e2-2f19-47b6-9bff-0e035ccee047.png)
![image](https://user-images.githubusercontent.com/68845761/153724226-dbba3d6b-a3db-4369-b911-48fbc64e3313.png)


# Dataset has been used:

* [Dataset link](https://www.kaggle.com/c/quora-question-pairs)

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/entbappy/Duplicate-Question-Pairs-NLP-Project
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n quora python=3.7.10 -y
```

```bash
conda activate quora
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
#run this file to generate the models
Data Analysis\bow-with-preprocessing-and-advanced-features.ipynb
```

Now run,
```bash
streamlit run app.py
```


```bash
Author: Bappy Ahmed
Data Scientist
Email: entbappy73@gmail.com

```

