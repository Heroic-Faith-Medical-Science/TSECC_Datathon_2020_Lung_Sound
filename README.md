# TSECC_Datathon_2020_Lung_Sound

Download the database from https://www.dropbox.com/s/5oanvakf53qq30t/Datathon.zip?dl=0.
There are two folders, "train" and "test", in the downloaded file.

Pairs of spectrogram image files (.tiff) and labeling file (.txt) can be found in the folders.

The spectrogram is derived from a 15-second lung sound using short time Fourier transform with nfft = 256, overlap = 192, no zero-padding.
The size of the spectrogram is 129 x 938. 

In the labeling files, you can find whether a spectrogram contains continuous adventitious sounds (CAS) or discontinuous adventitious sounds (DAS). 1 is True, and 0 is F
