# Digital_Filter_Design

Digital filters play a crucial role in digital signal processing (DSP), which is the field of study concerned with the analysis, processing, and manipulation of digital signals. They are used to filter out unwanted noise or interference, extract specific frequency components, and shape the frequency response of a system. They can be used in a wide range of applications, including audio and video processing, communications, control systems, and biomedical engineering.

The two main types of digital filters used in DSP are finite impulse response (FIR) filters and infinite impulse response (IIR) filters. FIR filters are characterized by a finite-length impulse response, meaning that they only respond to a finite number of input samples. IIR filters, on the other hand, have an impulse response that extends infinitely into the past and future.

Designing digital filters involves choosing the filter parameters, such as the cutoff frequency, passband ripple, and stopband attenuation, based on the specific requirements of the application. Several methods can be used to design digital filters, including windowing, frequency sampling, and optimization techniques such as least-squares or minimax approximation.

## Table of Contents

- [Built with](#Built-with)
- [Deployment](#Deployment)
- [Design](#Design)
- [Features](#Features)
- [Authors](#Authors)


## Built with

![programming language](https://img.shields.io/badge/programmig%20language-Python-red)
![programming language](https://img.shields.io/badge/programmig%20language-JavaScript-green)
This project is written in ![Python](https://img.shields.io/badge/Python-red) and ![JavaScript](https://img.shields.io/badge/JavaScript-green).
![Framework](https://img.shields.io/badge/Framework-Flask-blue)
![styling](https://img.shields.io/badge/Styling-CSS-ff69b4)


## Deployment

 Install streamlit

```bash
  pip install Flask
```
To start deployment 
```bash
  streamlit run main.py
```

## 🖌️ Design

![main widow](./images/mainwindow.png)

## Features
There is different modes : 
1. Uniform Range Mode: where the total frequency range of the input signal is divided uniformly into 10 equal
ranges of frequencies, each is controlled by one slider in the UI.
![main widow](./images/freq_mode.png)
also you can see the spectreogram
![main widow](./images/freq2.png)
2. Vowels Mode: where each slider can control the magnitude of specific vowel. You will need to do your own
research for how the speech vowels are composed of different frequency components/ranges.
![main widow](./images/vowels1.png)
also you can see the spectreogram
![main widow](./images/vowels2.png)
3. Musical Instruments Mode: where each slider can control the magnitude of a specific musical instrument in
the input music signal.
![main widow](./images/music1.png)
also you can see the spectreogram
![main widow](./images/music2.png)
4. Biological Signal Abnormalities: where each slider can control the magnitude of a specific abnormality (e.g.
ECG arrhythmia) in the input biological signal.
![main widow](./images/medical.png)






