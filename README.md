# Image Radiometry Lab

This repository contains practical exercises on **image acquisition and radiometry**, developed as part of a laboratory course in image processing.  
It covers histogram analysis, contrast adjustment, histogram equalization, dithering, gray-level statistics, and Fourier-based spectral analysis.

---

## 📖 Project Overview

The lab introduces fundamental **radiometric concepts in image processing**, focusing on how pixel intensity distributions and transformations affect image appearance and interpretation.  
It combines Python-based coding (NumPy, Matplotlib) with visual exploration in **GIMP**.

---

## 🛠️ Topics Covered

1. **Image Acquisition & Visualization**
   - Loading and displaying images in Python (with `matplotlib`).
   - Exploring zoom, scaling, and color spaces using **GIMP**.

2. **Gray Levels & Histograms**
   - Computing and visualizing histograms and cumulative histograms.
   - Adding Gaussian noise and analyzing its impact on histograms.
   - Contrast manipulation (brightness, curves, linear transforms).
   - Histogram equalization.
   - Histogram matching (prescription).

3. **Dithering**
   - Thresholding vs. dithering for binary images.
   - Noise-assisted quantization to simulate higher gray-level perception.

4. **Gray-Level Differences**
   - Statistics of pixel intensity differences between neighbors.
   - Gaussian distribution assumptions vs. real observations.

5. **Image Spectra & Fourier Transform**
   - Computing and visualizing image spectra.
   - Impact of windowing (Hamming) on spectral analysis.
   - Stripe image frequency characterization.
   - Subsampling effects on spectra.
   - Low-pass filtering (ideal vs. Gaussian).
   - Ringing effects and Fourier discontinuities.

---

## ⚙️ Requirements

- **Python 3.x**
- **NumPy**
- **Matplotlib**
- **GIMP** (for interactive visualization and histogram operations)

Install dependencies:

```bash
pip install numpy matplotlib
```
🚀 How to Run

1. Download or clone the repository.

2. Extract the images.tar archive into the images/ folder.

3. Run the starter Python script:
```bash
python Acquisition_radiometrie.py
```

4. Open and explore images in GIMP for tasks requiring manual interaction.