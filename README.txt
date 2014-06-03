speech-sentiment
================

Speech to Text Sentiment Analysis

Voice to text Sentiment analysis converts the audio signal to text to calculate appropriate sentiment polarity of the sentence.

The code currently works on one sentence at a time. Sentiment scoring is done on the spot using a speaker. The Speech to text processing system currently being used is the MS Windows speech to text converter. However significant modifications can be made for audio recognition by a refined signal processing system.

The sentiment operator in textblob is used for sentiment orientation scoring.

The code has been developed in Python 2.7

The following packages are required to be installed before running the program.

import speech

import sys

import time

import textblob

Links:

https://pypi.python.org/pypi/speech/0.5.2

http://textblob.readthedocs.org/en/dev/

Please contribute to this project to lead to a more refined and useful open source software.
