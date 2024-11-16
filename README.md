# Module 4 Requests, JSON, and basic NLP with spaCy

## Bukola Adeniyan 

## November 16, 2024

## Project Overview
Access web-based APIs for data.
Apply basic NLP and visualize result.

## Table of Contents
- [Instructions](#Instructions)
- [Requirements](#Requirements)
- [Installation](#installation)

## Instructions
a. Copy the base repository into your GitHub account by selecting the "Use this Template" button on GitHub and specifying yourself as the owner. The base repository is available at [https://github.com/wmnlp-materials/json-sentiment](https://github.com/wmnlp-materials/json-sentiment)

b. Clone YOUR new repo down to your machine.

c. On your machine, open the Jupyter Notebook to edit.

d. Required: After your name in your Markdown introduction, add a viewable, clickable link to your GitHub repo. You can build your brand and make your Markdown introduction clear and professional.

e. Required: Use Markdown headings (e.g., Question 1) to show your content clearly by each question number.

f. Complete the first task.

g. Execute the notebook. Commit and push to GitHub. Verify your notebook appears correctly.

h. Complete the second task.

i. Execute the notebook. Commit and push to GitHub. Verify your notebook appears correctly.

## Requirements
a. Markdown introduction with name and clickable link is required

b. Markdown Section Headings for each Question are required

c. Execute your code before exporting HTML and pushing notebooks (See FAQ for help.)

d. Unexecuted code is not eligible for credit

### Installation of SpaCy

```bash

python -m venv .env
.env\Scripts\activate
pip install -U pip setuptools wheel
pip install -U spacy
python -m spacy download en_core_web_sm
```

### Dependencies utilized

```bash

# Required dependencies
import requests
import json
import pickle
from textblob import TextBlob
from spacytextblob import spacytextblob
import spacy

# Addtional Dependencies 
import os
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
from wordcloud import WordCloud, STOPWORDS
import pandas as pd

```

### Special thanks to: https://course.spacy.io/en/
