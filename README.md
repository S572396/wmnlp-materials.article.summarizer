# Final Project: Article Summarizer
### SANDRA RUIZ
#### URL: https://www.tdcj.texas.gov/death_row/dr_executed_offenders.html


#### Introduction: This project will work with the url and pickle file for sentence and polarity analyisis. It will include histograms 
#### to answer specific token and lemmas quesitons. I will add in one cell for count analysis I am interesed in.

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

### Pre Set Up Cell:
##### Create and activate a Python virtual environment. 
###### Before starting the project, try all these imports FIRST
###### Address any errors you get running this code cell 
###### by installing the necessary packages into your active Python environment.
##### Try to resolve issues using your materials and the web.
###### If that doesn't work, ask for help in the discussion forums.
###### You can't complete the exercises until you import these - start early! 
###### We also import pickle and Counter (included in the Python Standard Library).


%pip install matplotlib
!pip install spacy
from collections import Counter
import pickle
import requests
import spacy
from bs4 import BeautifulSoup
import matplotlib.pyplot as plt

# List installed packages
!pip list

print('All prereqs installed.')***Sucessful

#### Question 2. Add in 
##### pip install requests spacy textblob
##### python -m spacy download en_core_web_sm

#### For my Own Analysis :
#### pip install pandas to env


## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Polarity score printed with an appropriate label: 1 pt
* (Question 2) Number of sentences printed: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Histogram shown with appropriate labelling: 1 pt
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Cutoff score seems appropriate given histograms: 2 pts (1/score)
* (Question 8) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 8) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 9) Polarity score printed with an appropriate label: 1 pt
* (Question 9) Number of sentences printed: 1 pt
* (Question 10) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 10) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 11) Polarity score printed with an appropriate label: 1 pt
* (Question 11) Number of sentences printed: 1 pt
* (Question 12) Thoughtful answer based on reported polarity scores: 1 pt
* (Question 13) Thoughtful answer based on summaries: 1 pt
