# Urban Sound Classification

## Data Set

This dataset contains 8732 labeled sound excerpts (<=4s) of urban sounds from 10 classes: air_conditioner, car_horn, children_playing, dog_bark, drilling, enginge_idling, gun_shot, jackhammer, siren, and street_music. The classes are drawn from the urban sound taxonomy. For a detailed description of the dataset and how it was compiled please refer to our paper.

All excerpts are taken from field recordings uploaded to www.freesound.org. The files are pre-sorted into ten folds (folders named fold1-fold10) to help in the reproduction of and comparison with the automatic classification results reported in the article above.

In addition to the sound excerpts, a CSV file containing metadata about each excerpt is also provided.

AUDIO FILES INCLUDED

8732 audio files of urban sounds (see description above) in WAV format. The sampling rate, bit depth, and number of channels are the same as those of the original file uploaded to Freesound (and hence may vary from file to file).

## Feature Extraction

We used the VGG-like model to generate the 128-dimensional features using the [audioset](https://github.com/tensorflow/models/tree/master/research/audioset/vggish) library available in the TensorFlow models Github repository, along with supporting code for audio feature generation, embedding postprocessing, and demonstrations of the model in inference and training modes.

[View the Jupyter Notebook Here](https://github.com/.ipynb)

The project involved cluster analysis and evaluation and drawing conclusions from the cluster data.

## Technologies Used
- Python, Numpy, Pandas, Matplotlib, Seaborn, SKLearn, Librosa, Audioset
- Jupyter Notebook
