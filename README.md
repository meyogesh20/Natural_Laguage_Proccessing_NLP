# Natural_Laguage_Proccessing_NLP
Natural Language Processing - NLTK

## How to set Conda Virtual Environment and to activate it.
create .yml file 
## 🔗 Sample can be downloaded from Links
[nlp_course_env.yml](https://drive.google.com/open?id=1pAU5zNhDN9EOxtKCEHK6LIPLtnLxeqkA)

Open Anaconda Prompt and Navigate to folder where env.yml is downloaded or placed.
```bash
  >cd Downloads
  >conda env create -f nlp_course_env.yml
```
To Activate/Deactivate this Environment, use
```bash
  >conda activate nlp_course
  >conda deactivate nlp_course
```

## How env.yml looks like

name: nlp_course
channels:
  - defaults
dependencies:
  - pip=18.1
  - spacy=2.0.16
  - numpy=1.15.4
  - keras
  - matplotlib=3.0.1
  - pandas=0.23.4
  - nltk=3.3.0
  - scikit-learn=0.20.1
  - jupyter=1.0.0

prefix: C:\Users\Marcial\Anaconda3\envs\nlp_course
