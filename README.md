# MFCC Speech Feature Extraction 🎙️

This repository contains a complete pipeline for extracting **Mel-Frequency Cepstral Coefficients (MFCCs)** from speech/audio signals using Python. MFCCs are one of the most widely used features in **Automatic Speech Recognition (ASR)** and **audio classification** tasks due to their ability to mimic human auditory perception.


## 📌 Project Highlights

- Pre-emphasis filtering
- Framing and windowing (Hanning/Blackman)
- Fast Fourier Transform (FFT) and Power Spectrum
- Mel filterbank computation
- Discrete Cosine Transform (DCT) to obtain MFCCs
- Delta (Δ) and Delta-Delta (Δ²) coefficients for capturing temporal dynamics
- Visualization of each processing step (waveforms, spectrograms, Mel filters, MFCCs)

---

## 📁 Folder Structure


.
├── data/                  # Input audio files (e.g. .wav)
├── output/                # Output plots and features
├── notebooks/
│   └── mfcc\_pipeline.ipynb    # Main Jupyter Notebook
├── README.md
└── requirements.txt       # Dependencies
---


## 🧪 Sample Plots

| Step | Visualization |
|------|----------------|
| Original Waveform | ![](output/main_wave.png) |
| Pre-emphasized Signal | ![](output/main_preemphasis.png) |
| Windowed Frames | ![](output/main_window_subplot.png) |
| FFT Spectrogram | ![](output/main_fft.png) |
| Mel Spectrogram | ![](output/main_mel.png) |
| Final MFCCs | ![](output/main_mfcc.png) |

---


## 📚 Background

This project was created as part of an academic exploration into **audio signal processing** and **speech feature extraction**. The methodology follows classical MFCC extraction as described in:

* Rabiner & Juang — *Fundamentals of Speech Recognition*
* Proakis — *Digital Signal Processing*
* Various ASR research papers

---

## 📧 Author

**Ronak Sarkar**
M.Sc. Big Data Analytics
RKMVERI, Belur Math
[LinkedIn](https://www.linkedin.com/in/ronak-sarkar-122a6130b/) • [Portfolio](https://sites.google.com/view/rsarkar)

---



Let me know if you want:
- A `requirements.txt` file
- Exportable code version (Python `.py`)
- Extended documentation (e.g., for delta formulas)
```
