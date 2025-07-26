# MFCC Speech Feature Extraction 🎙️

This repository contains a complete pipeline for extracting **Mel-Frequency Cepstral Coefficients (MFCCs)** from speech/audio signals using Python. MFCCs are fundamental features in **Automatic Speech Recognition (ASR)** and **audio classification** tasks due to their ability to mimic the human auditory system.

---

## 📌 Project Highlights

- ✅ Pre-emphasis filtering
- ✅ Framing and windowing (Hanning)
- ✅ Fast Fourier Transform (FFT) and Power Spectrum
- ✅ Mel Filterbank generation
- ✅ Discrete Cosine Transform (DCT) to obtain MFCCs
- ✅ Delta (Δ) and Delta-Delta (Δ²) coefficients for capturing speech dynamics
- ✅ Detailed visualizations at each processing step

---

## 🗂️ Project Structure

```

├── notebook/
│   └── extraction.ipynb            # Main notebook with full MFCC pipeline
├── output/                         # Output plots/images for each stage
│   ├── main_fft.png
│   ├── main_framing.png
│   ├── main_mel.png
│   ├── main_mfcc.png
│   ├── main_mfcc_delta.png
│   ├── main_preemphasis.png
│   ├── main_wave.png
│   ├── main_window.png
│   ├── main_window_subplot.png
│   ├── mfcc.png
│   └── spectrogram_windows.png
├── MelFrequencyCepstralCoefficients_Explained.pdf   # PDF explanation/report
├── README.md
└── requirements.txt                # Dependencies

````

---

## 📈 Visual Output Samples

| Step | Visualization |
|------|---------------|
| Original Waveform | ![](output/main_wave.png) |
| Pre-Emphasized Signal | ![](output/main_preemphasis.png) |
| Framing | ![](output/main_framing.png) |
| Windowed Frames | ![](output/main_window_subplot.png) |
| FFT Spectrum | ![](output/main_fft.png) |
| Mel Filter Output | ![](output/main_mel.png) |
| MFCC Coefficients | ![](output/main_mfcc.png) |
| Delta MFCC | ![](output/main_mfcc_delta.png) |

---

## 📄 How to Run

1. Clone this repo:
   ```
   git clone https://github.com/iamrsarkar/mel-frequency-cepstral-coefficients.git
   cd mel-frequency-cepstral-coefficients
````

2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:

   ```
   jupyter notebook notebook/extraction.ipynb
   ```

---

## 📘 Documentation

Refer to the full project report for in-depth explanations:

* **📄 [MelFrequencyCepstralCoefficients\_Explained.pdf](MelFrequencyCepstralCoefficients_Explained.pdf)**

The document explains:

* Signal preprocessing
* FFT & Mel scale theory
* Filterbank design
* MFCC, delta, and delta-delta coefficients

---

## 🧠 Author

**Ronak Sarkar**
M.Sc. Big Data Analytics
RKMVERI, Belur Math, India
[LinkedIn](https://www.linkedin.com/in/ronak-sarkar-122a6130b/) • [GitHub](https://github.com/iamrsarkar) • [Portfolio](https://sites.google.com/view/rsarkar)

---

## 📜 License

This project is licensed under the MIT License. Feel free to use or modify for academic/non-commercial purposes.

```

---

Let me know if you want me to generate:
- A `requirements.txt` file from your environment
- A `.py` version of the notebook for script execution
- GitHub Pages for documentation or demo visuals
```
