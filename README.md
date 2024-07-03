# Tesi-Image_Sketch_Captioning

## Overview
Questa repository contiene il progetto del mio Tirocinio e Tesi per la Laurea Triennale in Ingegneria Informatica.

Il progetto si focalizza sull'"Image e Sketch Captioning": dato un input sotto forma di immagine o sketch, sono stati sviluppati e testati diversi modelli di Deep Learning in grado di generare una descrizione che cattura il significato complessivo dell'immagine.

In particolare, il lavoro si basa su modelli encoder-decoder, dove l'encoder utilizza una rete neurale convoluzionale (CNN) per estrarre le caratteristiche (features) dalle immagini, mentre il decoder impiega una rete neurale ricorrente (RNN) per generare la descrizione (caption).


## Tesi
La Tesi è disponibile [qui]().
## Datasets
- Flickr8k
- Flickr8k_sketchified (creato personalmente convertendo le immagini in sketch)
- sketch-scene
## Codice
I diversi file differiscono principalmente per dataset, tecniche e reti neurali utilizzate.
- **Dataset:Flickr8k, CNN:VGG16, RNN:SimpleRNN, Lemmatizzazione:No**
  [Link al Codice CNN]().

- **Dataset:Flickr8k, CNN:Xception, RNN:LSTM, Lemmatizzazione:Si**

- **Dataset:Flickr8k_sketchified, CNN:Xception, RNN:LSTM, Lemmatizzazione:Si**

- **Dataset:sketch-scene, CNN:Xception, RNN:LSTM, Lemmatizzazione:Si**

- **Dataset:sketch-scene, CNN:Xception, RNN:LSTM, Lemmatizzazione:No**

## Crediti
- Tommaso Senatori
