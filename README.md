# Beatwell API

The **Beatwell API** provides wellness-related and physiological signal analysis (PPG, ART, ABP) based on uploaded files. Physiological signal represents the cardiovascular activity that is translated as heart beat pulses.
It is designed to be easily integrated into R&D pipeline that is working with health and wellness data.

## 🚀 Demo
You can try the API through our online demo:  
👉 https://beatwell.tech/demo  

In the demo, you upload a file and receive processed results from our backend engine (built in PHP).

## 📌 How it Works
1. Upload a .csv file that contains signal samples to the web interface.
2. Type the sampling frequency used during physiological signal acquisition.
3. The server processes the file.  
4. It displays a plot with inputted signal and the analysis it performs.

## ✨ Features
1. Selects only the good heart beats waveforms by avoiding the corrupted ones (noise, artifacts).
2. Displays the heart beat rate for the selected beats.
3. Displays the presence of arrhythmia as level.
