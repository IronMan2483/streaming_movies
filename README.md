# __Streaming services: Movies__

The most difficult decision is the following one: Which movie we want to see tonight?

There are a lot of streaming provider out there but the 2 biggest one are for sure Prime Video and Netflix.

The dataset I used contains data from 4 streaming provider: Prime Video, Netflix, Hulu and Disney+. 

For sure I could also add Sky, Apple or others, but I want to focus on the biggest global provider.


<img src="https://help.nflxext.com/43e0db2f-fea0-4308-bfb9-09f2a88f6ee4_what_is_netflix_1_en.png" width=760 height=450 />


__In this project I want to get an overview of:__
* the numbers of movies on the 4 streaming provider
* what are the most common genres
* which runtime -> also important for making the decision for the tonight's movie :-)
* what are the most common languages
* which directors are the most common ones
* which genres are the most common ones in German


---

Dataset: This dataset is from [Kaggle](https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney?select=MoviesOnStreamingPlatforms_updated.csv).

---

## __Requirements__

pyenv with Python: 3.9.4

---

## __Environment__

`````
pyenv local 3.9.4

python -m venv .venv

source .venv/bin/activate

pip install --upgrade pip

pip install -r requirements.txt


brew update

brew install node


pip install jupyterlab "ipywidgets>=7.5"

jupyter labextension install jupyterlab-plotly@4.14.3

jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.14.3
```````````
