# Jellyfish Galaxy Identification with Machine Learning

final_classified_sample_clusters.csv has the real labels for the galaxy sample and also their ids and coordinates

Step 1: use "download-stamps.ipynb" to download the images for each galaxy in the sample

Step 2:now you have a folder with all the galaxies, use "jelly-model.ipynb" to make a new catalog that works for zoobot, using the labels and ids from before.

Step 3: install the following dependencies:
!pip install galaxy_datasets
!pip install lightning
!pip install zoobot
!pip install tokenizer

run "jelly-model.ipynb" to train the model and obtain diagnostics and metrics.

please pay attention to the comments because the code is rather desorganized, especially in the diagnostics section.

