# repo for kaggle competition

## Installation

clone this repo
```bash
git clone https://github.com/aronei44/kaggle-competition.git
cd kaggle-competition
```

environment preparation
```bash
py -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
```
for windows. (for mac and linux is different in prepare for virtual env)

if you have an error with `nltk`

just run this in your ipynb / python file

```py
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

happy coding
