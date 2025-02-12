# 🎤 Voice Cloning Model Evaluation

## 🚀 Overview
This repository provides a comprehensive evaluation of voice cloning models based on objective speech quality metrics. Our goal is to assess the effectiveness of these models in generating high-quality, intelligible, and natural-sounding voices.

## 📈 Models Evaluated

| **Model**  | **PESQ** | **STOI** | **MCD**  | **Pitch Corr** | **Spec Conv** | **Energy Ratio** | **SNR (dB)**  |
|------------|---------|---------|---------|-------------|------------|--------------|------------|
| OpenVoice  | 1.165   | 0.136   | 37.988  | -0.027      | 3.475      | 12.305       | -11.193    |
| CoquiTTS   | 1.727   | 0.143   | 203.193 | 0.012       | 6.675      | 45.896       | -16.717    |
| F5-TTS     | 1.782   | 0.171   | 174.265 | 0.060       | 6.082      | 39.209       | -16.065    |
| E2-TTS     | 2.281   | 0.165   | 158.578 | -0.051      | 5.760      | 34.939       | -15.551    |

## 🔬 Evaluation Metrics

- **PESQ (Perceptual Evaluation of Speech Quality):** Measures speech quality, with values ranging from -0.5 to 4.5 (higher is better).
- **STOI (Short-Time Objective Intelligibility):** Assesses how well the synthesized voice is understood (range: 0 to 1, higher is better).
- **MCD (Mel Cepstral Distortion):** Lower values indicate more accurate voice cloning.
- **Pitch Correlation:** Measures how closely the pitch matches the original speaker (closer to 1 is better).
- **Spectral Convergence (Spec Conv):** Evaluates how well spectral features align (lower is better).
- **Energy Ratio:** Assesses energy distribution in frequency bands.
- **SNR (Signal-to-Noise Ratio in dB):** Higher values indicate cleaner, more natural output.

## 🌐 Test the Models
You can experiment with each model using the provided links:

- **OpenVoice:** [Try Here](https://colab.research.google.com/github/camenduru/OpenVoice-colab/blob/main/OpenVoice_colab.ipynb)
- **TortoiseTTS:** [Try Here](https://colab.research.google.com/drive/1ipQ3UyGsWl8h2CEgzpkmpofjmCstKm4P#scrollTo=u30gPA_G4fhW)
- **E2-F5-TTS:** [Try Here](https://huggingface.co/spaces/mrfakename/E2-F5-TTS)
- **CoquiTTS:** [Try Here](https://colab.research.google.com)

## 🎡 Summary & Recommendations
- **Best for natural voice quality:** E2-TTS (highest PESQ, lowest MCD).
- **Best for intelligibility:** F5-TTS (highest STOI score).
- **Moderate performance:** CoquiTTS (balanced results but high spectral distortion).
- **Least recommended:** OpenVoice (low PESQ, less realistic output).


## 🔗 References
- Research papers on voice cloning and speech synthesis.
- Documentation for OpenVoice, CoquiTTS, F5-TTS, and E2-TTS.
- AI community benchmarks for objective speech evaluation.

For more updates and evaluations, check out the full repository on **GitHub**! 💻
