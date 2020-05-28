# Generating a Doppelganger Graph:Resembling but Distinct

This repository provides a pytorch implementation of this paper:
> Generating a Doppelganger Graph:Resembling but Distinct


## Requirements

The code is implemented in Python 3.6. To run the code, these required packages are needed to install:

```
numpy
networkx
scipy
python-igraph
powerlaw
scikit-learn
matplotlib
pytorch
statsmodels
```

## Run the code
 
The two folder contains different dataset, different codes and different pretrained model.
 
In order to get the link prediction model, run `sample_graphsage.ipynb`. 

In order to get the GAN result, run `sample_GAN.ipynb`.

In order to get the generated graph, run `generate_graph.ipynb`.

## Pretrained model

We have already provided the pretrained link prediction model:`embeddings.npy` and embeddings `embeddings.npy`.

We have already provided the pretrained GAN model:`gan_model\bestG_pretrained.pth` and embeddings `gan_model\bestD_pretrained.pth`.
