# DLND-Language-Translator
Using Recurrent Neural Network, sequence to sequence model is trained on a dataset of English and French sentences, that can translate new sentences from English to French.

## Imperfect Translation
Some sentences translate might better than others. Since the dataset used only has a vocabulary of 227 English words of the thousands used, results will be shown accordingly, in this case(project), is pretty good. 

Additionally, the translations in this data set were made by Google translate, so the translations themselves aren't particularly good. (We apologize to the French speakers out there!) Thankfully, for this project, a perfect translation is not the requirement. However, if you want to create a better translation model, you'll need better data.

You can train on the [WMT10 French-English corpus](http://www.statmt.org/europarl/). This dataset has more vocabulary and richer in topics discussed. However, this will take you days to train, so make sure you've a GPU and the neural network is performing well on dataset we provided.

## Built with
- [Tensorflow](https://www.tensorflow.org/install/) - The machine learning framework
- [Anaconda](https://www.anaconda.com/)
- [Jupyter Notebook](http://jupyter.org/install)  


