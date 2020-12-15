# 11785 Final Project - Local Minimum

## Baseline 
To run the baseline, simply run the cells in order in Baseline.ipynb. This download/runs the test-clean set from Librispeech on the pretrained model found here: https://zenodo.org/record/3966501. It uses Levenshtein to find the average edit distance between the predictions from the model and the real transcripts of the audio files. 

## Experiments
The experiments are contained in the ctc_decode.ipynb notebook. To run, download the AN4 dataset (.sph) format and edit the path to the correct location in the code. This is the implementation of the CTC loss with viterbi decoding, and the bugs encountered are described in the Final Report's Experiments and Results section. 
