# Audio-Based-Bird-Species-Classification
Identification of various bird species from audio files.

Tools Used :
<pre>

@ Web scraper to download audio data from Xeno-Canto (https://www.xeno-canto.org). 

			===>  https://github.com/AgaMiko/xeno-canto-download
			
			
                  
@ Libraries: 

			===>	Librosa, Tensorflow


Flow :

@ Download audio data samples using above web scraper.

@ Preprocess data and extract MFCC array usning __extract features__ function.

@ Create .csv file from MFCC data.

@ Build ANN / CNN model.

@ Train and predict accuracy.



Notebooks :

@ Extract.ipynb     ===>   Extract features and create .csv file

@ Load_csv.ipynb    ===>   Loads csv file + Builds and  Trains the model.


</pre>
