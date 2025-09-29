# Deep Learning-Assisted Dynamic Mode Decomposition (DA-DMD)

---

### 🔬 Overview
**DA-DMD** is a physics-informed framework for **removing non-resonant background (NRB)** in 
Coherent Anti-Stokes Raman Spectroscopy (**CARS**) using:

- **Dynamic Mode Decomposition (DMD):** Unsupervised spectral separation.  
- **Deep Learning with channel attention + CNN:** Adaptive weighting of DMD modes for robust Raman signal recovery.

---

### 📄 Paper
Our method is described in:  
**Deep Learning-Assisted Dynamic Mode Decomposition for Non-resonant Background Removal in CARS Spectroscopy**  
[📥 Download PDF](valapil2025dadmd.pdf)

---

### 💻 Code
Implementation available here:  
👉 [GitHub Repository](https://github.com/spectra-analysis/DA_DMD)

---

### 📊 Results
- Removes broadband NRB without reference spectra.  
- Fast inference (<10 ms per spectrum).  
- State-of-the-art accuracy on synthetic & real CARS data.  

![DA-DMD Framework](images/da_dmd_framework.png)

---

### 🎥 Video (coming soon!)
We plan to add a short video introducing DA-DMD.

---

### 👥 Authors
Adithya A.C. Valapil, Carl Messerschmidt, Maha Shadaydeh, Michael Schmitt,  
Jürgen Popp, Joachim Denzler
