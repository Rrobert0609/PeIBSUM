# Peibsum
## Description
This here is another project for the "Marisiensis" competition hosted by my university. It is a recurrent neural network that trains on certain patients' ECG analyses and is able to tell which patient took any new analysis that it is given.
## How I made it
This is a python code that uses the LSTM and GRU models from the Keras module as the two RNNs for the identification, compares the two of them to see which one is better, and tests them on new analyses to see how they perform. 
## What I used
For this project I used the NumPy, Pandas, Matplotlib, WFDB, TensorFlow, Keras and SciKitLearn modules and the MIMIC-IV EEG analyses dataset which is publicly available on the PhysioNet website (bear in mind, there is a chance that their servers will be so bad that you will have to download a 30gb zip at 200kb/s).
## Why I did this for the competition and not something else
I saw the patent that Apple made where they wanted to implement into some of their devices the ability to learn your ECG patterns and detect that it is you who wants to use said device based solely on the patterns that it detects when you want to use it, and unlock your device automatically, no password, no nothing. Seeing this, I thought "How hard would it be to identify someone based solely on ECG analyses?". I basically started seeing this as a privacy issue, thinking that some weirdo with more money than me, more time than me and more expertise with neural networks could scour the dark web, look for data breaches from hospital or medical clinics to find ECG analyses, separate the ones where the patient names are availabe from the ones where they aren't, and find out from which patients the "unknown" recordings are, this way being able to find out if those patients have any sort of heart related problems. From here they could maybe use the information they find to do some sort of scummy stuff, and from what I gathered, this seems quite possible, even simple for someone with, as I said earlier, more money, more time and more experience.

So yeah, kinda weird but it made for a fun and interesting project.
