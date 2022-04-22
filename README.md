#  FastText.py
Porting to Pytorch of [fastText](https://github.com/facebookresearch/fastText)
## How to install libraries

```
git clone https://github.com/loretoparisi/fasttext.py.git
cd fasttext.py/fasttext
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

## How to install datasets
```
cd data/
wget https://nlp.stanford.edu/data/wordvecs/glove.840B.300d.zip
unzip glove.840B.300d.zip
```

## How to train

```
cd fasttext.py/fasttext
$ python train.py

Final Training Accuracy: 0.9006
Final Validation Accuracy: 0.8948
Final Test Accuracy: 0.8929

```

## Disclaimer
Code adapted from https://github.com/AnubhavGupta3377/Text-Classification-Models-Pytorch
