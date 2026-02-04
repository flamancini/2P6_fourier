**2P6: Signal Processing and Data Analysis**

University of Cambridge, Department of Engineering

Lecturer: Flavia Mancini

📌 **About This Repository**

This repository contains a Jupyter Notebook designed for students enrolled in the 2P6: Signal Processing and Data Analysis course at the University of Cambridge, CUED. The notebook provides an interactive learning environment to explore key signal processing concepts through practical Python implementations.


🚀 **Getting Started**

1️⃣ Clone the Repository

To get started, clone this repository to your local machine:
```python
git clone https://github.com/flamancini/2P6_fourier.git
cd 2P6_fourier
```

2️⃣ We are using Jupyter Notebooks, please install dependencies inside the notebook:

```python
!pip install numpy scipy matplotlib sounddevice
```

3️⃣ Run the Notebook

Launch Jupyter Notebook and open the files:

```python
jupyter notebook notebooks/FFT_demo.ipynb
jupyter notebook notebooks/Fourier_Transform_Linear_Algebra.ipynb
```

🛠 **Features & Implementations**

📌 **handouts_3_4_integral_demos.ipynb** — Fourier Transform via Integrals (No FFT)
This notebook accompanies **Handouts 3 and 4** of the course and is designed to
build *conceptual understanding* of the continuous-time Fourier Transform.
We deliberately **avoid FFTs and DFTs**.  
All spectra are computed by **numerical quadrature** (Riemann / trapezoidal
approximations of the Fourier integral)
\[
F(\omega)=\int_{-\infty}^{\infty} f(t)\,e^{-j\omega t}\,dt.
\]
The goal is to focus on *what the Fourier Transform means*, rather than how it is
implemented efficiently on a computer. This notebook supports the theory lectures by making the Fourier Transform feel
like “an integral that adds rotating phasors.” Once this intuition is secure, FFT-based methods are much easier to understand
and trust.

📚 Recommended use:
• Read alongside **Handouts 3 and 4**  
• Run cells slowly and inspect intermediate plots  
• Answer the inline questions before moving on  

🔍 This notebook demonstrates: Continuous spectra, Time–frequency trade-offs, Time shift, Frequency shift / modulation, Convolution theorem (time ↔ frequency), Duality

📌 **FFT_demo.ipynb**
This notebook will help you:
Generate and analyze signals (chirp, sine wave, aliased chirp, and music signals).
Understand the Fourier Transform and its applications.
Visualize signals in the time domain and frequency domain.
Compute and interpret spectrograms for time-varying frequency content.
Save and play signals as WAV audio files.

📌 **Fourier_Transform_Linear_Algebra.ipynb**
This notebook will help you understand the Fourier Transform from a linear algebra perspective, including concepts like basis transformations, eigenvalues, and matrix operations. It demonstrates the DFT as a matrix transformation and compares it with the FFT, providing an intuitive and computational approach to signal processing. 🚀


📬 Contact

For any queries regarding this notebook or the 2P6 course, reach out to Flavia Mancini.

📧 Email: [flavia.mancini@eng.cam.ac.uk]


