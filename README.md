Download the dataset here: [Stream-51](https://drive.google.com/file/d/15huZ756N2cp1CCO4HxF-MVDsMx1LMoIn/view?usp=sharing)

## What is streaming classification?

Instead of traditional image classification datasets which train on thousands of independent images per object, we built a dataset made up of dozens of small snippets of videos.

Training a classification model in this way forces the model to generalize from highly correlated images and approximates how real-time agents must learn to classify objects.  

## Why include novelty detection?

In addition to streaming data we also establish protocols for novel object identification by including novel classes in our evaluation set that are unseen during the training sequences.

## What does our dataset contain?

## How can I create a Dataset or Dataloader?
Within the downloaded files are two pickle files containing a python list which lists out each image file and the source class, video, and clip within the dataset.  To organize the dataset for training in Pytorch via one of the baseline orderings we have provided a sample dataset class and dataloader function within the 'StreamDataset.py' file above
