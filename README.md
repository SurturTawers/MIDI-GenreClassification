# MIDI-GenreClassification
MIDI Genre Classification using the Lakh Midi Dataset in Tensorflow Keras on Google Colab.

## Details
Using:
* Lakh Midi Dataset (https://colinraffel.com/projects/lmd/)
* MSD tagtraum for the genres (https://www.tagtraum.com/msd_genre_datasets.html).\
\
I tried extracting the features of the MIDI tracks using prettyMIDI to train the NN and predict the genre from the midi.\
In the actual state of the code, it overfits to pop-rock due to the excessive amount of pop-rock MIDI tracks.
