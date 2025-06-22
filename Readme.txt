📊 FFT Signal Analysis and Simulation Projects


This repository contains a set of three projects developed as part of a university case study assignment (Open University MST374 – Computational Applied Mathematics). Each project demonstrates the application of the Fast Fourier Transform (FFT) in a different context: theoretical analysis, real-world audio signal processing, and stochastic system simulation.

📁 Part 1: Fourier Transform of a Periodic Function (cosh)


Description


This project analyses the Fourier Transform of a periodic version of the hyperbolic cosine function (cosh). The function is extended to be periodic using symmetric reflections, and the FFT is applied to the resulting signal.



Highlights
Constructed a periodic function from a non-periodic base using reflections

Applied FFT with norm='forward' for physical consistency

Computed analytical Fourier Transform for comparison

Plotted FFT magnitude and overlaid analytical spectrum to validate numerical output



📁 Part 2: Guitar Chord Frequency Analysis with FFT


Description


This project analyses .wav audio recordings of guitar chords to extract and identify the individual notes present in each chord. Frequency domain analysis is performed using the FFT, and notes are matched against known chord definitions.



Highlights
Read .wav files using SciPy and extracted sample data

Applied FFT and computed energy spectrum

Peak frequency detection with filtering of noise components

Mapped dominant frequencies to musical notes

Identified full chords using CSV-based note definitions




📁 Part 3: Stochastic Resonance in a Bistable System


Description


This project simulates a particle in a bistable potential with weak periodic forcing and Gaussian white noise. Using the Euler-Maruyama method for SDEs, it demonstrates the phenomenon of stochastic resonance by analysing how signal amplification varies with noise intensity.



Highlights
Simulated sample paths of the stochastic differential equation

Performed FFT on output signals to extract signal power

Averaged spectra over multiple paths to reduce noise

Computed and plotted spectral amplification as a function of noise strength (D)

Observed resonance peaks at optimal noise levels



Danilo Pierpaoli

Acknowledgements:

Open University – MST374 Computational Applied Mathematics

