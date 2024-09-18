# Tesi-Image_Sketch_Captioning

## Overview
Questa repository contiene il progetto del mio Tirocinio e Tesi per la Laurea Triennale in Ingegneria Informatica.

Il progetto si focalizza sull'"Image e Sketch Captioning": dato un input sotto forma di immagine o sketch, sono stati sviluppati e testati diversi modelli di Deep Learning in grado di generare una descrizione che cattura il significato complessivo dell'immagine.

In particolare, il lavoro si basa su modelli encoder-decoder, dove l'encoder utilizza una rete neurale convoluzionale (CNN) per estrarre le caratteristiche (features) dalle immagini, mentre il decoder impiega una rete neurale ricorrente (RNN) per generare la descrizione (caption).


## Tesi
La Tesi è disponibile [qui](TesiTommasoSenatori.pdf).
## Datasets
- [Flickr8k](https://www.kaggle.com/datasets/adityajn105/flickr8k)
- [Flickr8k_sketchified](https://www.kaggle.com/datasets/tommasosenatori/flickr8k-sketch) (creato personalmente convertendo le immagini in sketch, usando una tecnica illustrata in [questo codice](how_to_sketch.ipynb)).
- [sketch-scene](https://huggingface.co/datasets/zoheb/sketch-scene)
## Codice
I diversi file differiscono principalmente per dataset, tecniche e reti neurali utilizzate.
- **Dataset:Flickr8k, CNN:VGG16, RNN:SimpleRNN, Lemmatizzazione:No** --> [Flickr8k Standard](ImageCaptionInd.ipynb).

- **Dataset:Flickr8k, CNN:Xception, RNN:LSTM, Lemmatizzazione:Si** --> [Flickr8k Advanced](ImageCaptionSit.ipynb).
- **Dataset:Flickr8k_sketchified, CNN:Xception, RNN:LSTM, Lemmatizzazione:Si** --> [Flickr8k_sketchified](SketchifiedCaption.ipynb).
- **Dataset:sketch-scene, CNN:Xception, RNN:LSTM, Lemmatizzazione:Si** --> [sketch-scene (lemma)](SketchCaption.ipynb).
- **Dataset:sketch-scene, CNN:Xception, RNN:LSTM, Lemmatizzazione:No** --> [sketch-scene (no lemma)](SketchCaption(no_lemma).ipynb).
## Crediti
- Tommaso Senatori
