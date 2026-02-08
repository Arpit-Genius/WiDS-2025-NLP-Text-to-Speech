# WEEK 4 - Introduction to Speech Processing
## CONCEPTS
What Is Speech?  

Audio Signal Basics - Sampling rate (Nyquist theorem), Amplitude & dynamic range, Mono vs stereo, Bit depth  

Time–Frequency Representations - Short-Time Fourier Transform (STFT), Spectrograms, Log spectrograms, Why spectrograms?  

Mel Scale & MFCCs - Human auditory perception, Mel frequency scale, Mel spectrograms, MFCC pipeline(STFT, Mel filterbanks, Log compression, DCT)  

Speech Recognition Approaches - Classical STT, Neural STT

## CODING TASKS
AUDIO LOADING and INSPECTION - Loaded .wav files(M1F1-int16-AFsp.wav), Checked duration and sampling rate, Normalized amplitude  

VISUALISATION - Plotted waveform, spectogram, Mel spectrogram, MFCCs  

FEATURE EXTRACTION PIPELINE - Framing and windowing, feature normalization  

Colab Notebook Link - https://colab.research.google.com/drive/13wZpJ91EuW9gjLH2I_oaFxs9PgWpN6Ds?usp=sharing

### KEYWORD SPOTTING MODEL
TASK - Binary classification: “yes” vs “no”  

DATA -  
YES samples  
!wget -q -P data/yes https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/0_jackson_0.wav  
!wget -q -P data/yes https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/0_george_0.wav  
!wget -q -P data/yes https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/0_nicolas_0.wav  

NO samples  
!wget -q -P data/no https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/1_jackson_0.wav  
!wget -q -P data/no https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/1_george_0.wav  
!wget -q -P data/no https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/1_nicolas_0.wav   

# MINI-PROJECT
## SPEECH FEATURE EXTRACTION
### AUDIO FILES 
YES samples (digit "0")  
!wget -q -P data/yes https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/0_george_0.wav  
!wget -q -P data/yes https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/0_jackson_0.wav  
!wget -q -P data/yes https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/0_nicolas_0.wav  

NO samples (digit "1")  
!wget -q -P data/no https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/1_george_0.wav  
!wget -q -P data/no https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/1_jackson_0.wav  
!wget -q -P data/no https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/1_nicolas_0.wav  

EXTRACTS - Spectogram, Mel Spectogram, MFCCs  

Comapred features across different words  

Colab Notebook Link - https://colab.research.google.com/drive/1yaPD3BfVvhV6CMATJlGFcjYxQa2sM_ot?usp=sharing
