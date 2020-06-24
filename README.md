음악 장르 패턴 인식 및 분류기 구현(CNN+GRU)
=============

Dataset for this project
-------------
This dataset was used for the well known paper in genre classification "**Musical genre classification of audio signals**" by G. Tzanetakis and P. Cook in IEEE Transactions on Audio and Speech Processing 2002.
Unfortunately the database was collected gradually and very early on in my research so I have no titles (and obviously no copyright permission etc). The files were collected in 2000-2001 from a variety of sources including personal CDs, radio, microphone recordings, in order to represent a variety of recording conditions. Nevetheless I have been providing it to researchers upon request mainly for comparison purposes etc. Please contact George Tzanetakis (gtzan@cs.uvic.ca) if you intend to publish experimental results using this dataset.
The dataset consists of 1000 audio tracks each 30 seconds long. It contains 10 genres, each represented by 100 tracks. The tracks are all 22050Hz Mono 16-bit audio files in .wav format.
Download **GTZAN** in http://marsyas.info/downloads/datasets.html

Framework & Library 
-------------
librosa, numpy, keras
