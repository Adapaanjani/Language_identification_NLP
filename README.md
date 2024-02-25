# Audio-language-identification

## Objective
Language Identification (LID) is broadly defined as recognizing the language of a given speech utterance. It has numerous applications in automated language and speech recognition, multilingual machine translations, speech-to-speech translations, and emergency call routing. In this project, we will try to classify five languages( Hindi, Irish, Hungarian, Japanese, Punjabi) from the Audio clips used from open-source dataset Common Voice. We will implement a three models (Resnet50, Inception V3 and a basic CNN), and train them to classify the languages using Keras. 

## Dataset
Data Folder contains the data files in mp3 format already segregated into respective language folders. COMMON VOICE Dataset originally contains large no of files and has uneven distribution among languages. So a subset of 200 files is taken for each language. 
The `validated.tsv` file is used to map the audio files to the language spoken in it. present separately in each language folder.

Train and test folder are created by the code dividing the train and test files in desired ratio.

## Requirements
- TensorFlow
- librosa
- Python 2.7+


## Sample length
Audio sample varies from 3 sec to 7sec.
## Audio Format
The wav files have 22500 sampling rate, single channel.

## Notes about the code
Scroll down the warning messages in code.
code works in following manner:-

- Firstly the files from data folder are segregated into train and test folders. 
- Then to prepare input for the models Spectrogram images are generated with and without noise for the same audio file.
- Using these spectrogram files models are trained.
- at last models are tested using test folder files.
