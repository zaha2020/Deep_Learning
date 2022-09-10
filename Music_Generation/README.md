# Generating music using LSTMs


## Dataset
We've used `MIDI Music Class` for generating music using LSTMs. from various artists, we've chosen melodies from Chopin Frédéric and Mozart.
several preprocessing steps have been done on the data before training:
- Removing rare notes
- Creating a corpus of notes
- Generating sequences
- Considering the note after the end of the sequence as a label
- One-hot encoding for labels


## Train
After doing preprocessing steps, We've used LSTMs to generate Music. For this purpose, we generate notes and after that, we convert these generated notes to music with the help of the `music21` python library.

Below is the loss function during training for an LSTM Network with dropout and without dropout:
![loss](loss.png "loss")


