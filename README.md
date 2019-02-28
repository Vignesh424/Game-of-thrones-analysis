# Game-of-thrones-analysis
Analysis of GoT dialogues using NLP techniques. 

The main question I would like to answear is how dialogues relate characters in GoT series, and what we can learn from those relationships. 

You can learn more about the motivation for this project in this post.

# Install

This project requires **Python 3.6** and the following Python libraries installed:

- [numpy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)
- [fastai](https://github.com/fastai/fastai)
- [networkx](https://networkx.github.io/documentation/stable/install.html)
- [nltk](https://www.nltk.org/install.html)
- [genism](https://radimrehurek.com/gensim/install.html)

## Data

I obtained the raw dialogues from [Genius.com](https://genius.com/artists/Game-of-thrones), these were trancribed by volunteers, so not all
seasons are there and of course you will found some mistakes, but is the best there is. Also I encourage you to participate and transcribe some dialogues yourself, it will be so cool to have all the seasons transcribed for further analysis. 

All the csv files I will use are available [here](https://github.com/chrismartinezb/Game-of-thrones-analysis/tree/master/CSV), and you can find how I transform the raw text into a more useful csv in the [Final Pipeline](https://github.com/chrismartinezb/Game-of-thrones-analysis/blob/master/Final%20Pipeline.ipynb) notebook.

## Network Graph

You can play with it in the following link.

[Graph](https://bl.ocks.org/chrismartinezb/e35f6c6b7a4def1dc56eea92d8897d40/ee9d335a443b042fc20c2f2eb0d55e9997d2f2b9)

## Dialogue generation.


## Licensing, Authors, Acknowledgements
I have to give credit to all the volunteers at Genius for transcribing the dialogues as well as to [Paras Chopra](https://towardsdatascience.com/generating-new-ideas-for-machine-learning-projects-through-machine-learning-ce3fee50ec2) and [Daniel E. Licht](https://lichtphyz.github.io/) whose work is the base of this project. Apart from that feel free to use the code and files as you wish.


