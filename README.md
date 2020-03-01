# Urban Sound Classification
Un-Supervised Learning Capstone Project 

Sonic event classification is a field of growing research. Most of these researches focuses on music or speech recognition. There are scarce works on environment sounds with very few databases for labeled environment audio data.

In this capstone project, UrbanSound8K Audio Dataset was used. 


## Data Set

The dataset is comprised of 8732 slices (audio excerpts) of up to 4 s in duration extracted from field recordings crawled from the Freesound online archive.

Each slice contains one of 10 possible sound sources: air conditioner, car horn, children playing, dog bark, drilling, engine idling, gun shot, jackhammer, siren, street music.

All excerpts are taken from field recordings uploaded to www.freesound.org. The files are pre-sorted into ten folds (folders named fold1-fold10) to help in the reproduction of and comparison with the automatic classification results reported in the article above.

In addition to the sound excerpts, a CSV file containing metadata about each excerpt is also provided.

AUDIO FILES INCLUDED

8732 audio files of urban sounds (see description above) in WAV format. The sampling rate, bit depth, and number of channels are the same as those of the original file uploaded to Freesound (and hence may vary from file to file).

## Feature Extraction

We used the VGG-like model to generate the 128-dimensional features using the [audioset](https://github.com/tensorflow/models/tree/master/research/audioset/vggish) library available in the TensorFlow models Github repository, along with supporting code for audio feature generation, embedding postprocessing, and demonstrations of the model in inference and training modes.

[View Feature Extraction Here](https://github.com/rajinigurijala/Capstone4/blob/master/ExtractFeatures.ipynb)

## Cluster Analysis

The project involved cluster analysis and evaluation and drawing conclusions from the cluster data.

[View Cluster Analysis Here](https://github.com/rajinigurijala/Capstone4/blob/master/UrbanSoundUnsupervised.ipynb)

## Technologies Used
- Python, Numpy, Pandas, Matplotlib, Seaborn, SKLearn, Librosa, Audioset
- Jupyter Notebook
