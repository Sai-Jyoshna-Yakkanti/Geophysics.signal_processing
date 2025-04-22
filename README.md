# Geophysics Signal Processing

This repository contains a series of Jupyter Notebooks demonstrating signal processing techniques and their application in geophysics. The main focus of this project is on physics-based modeling, Fourier transforms, noise filtering, and seismic wave simulations.

## Notebooks

### 1. FFT Analysis (`1_fft_analysis.ipynb`)
This notebook demonstrates the use of the Fast Fourier Transform (FFT) to analyze a simple sine wave signal.

### 2. Lowpass Filtering (`2_lowpass_filtering_experiment.ipynb`)
In this notebook, we experiment with filtering techniques, applying low-pass filters to clean noisy signals.

### 3. Multi-Frequency FFT (`3_multi_freq_fft.ipynb`)
This notebook showcases FFT analysis on a signal with multiple frequencies, illustrating how to extract frequency components from complex signals.

### 4. Seismic Wave Simulation (`4_seismic_wave_simulation.ipynb`)
Here, we simulate seismic waves and demonstrate how FFT and signal processing can be applied to understand subsurface geology.

## Requirements

To run the notebooks, ensure you have the necessary dependencies installed. You can create a conda environment and install the required packages using the provided `environment.yml` file:

```bash
conda env create -f environment.yml

## Usage
To get this project up and running on your local machine, follow these steps:

Activate the environment:

conda activate seismic_env
This command activates the Conda environment where all necessary dependencies for this project are installed.

Run the Jupyter Notebook:

jupyter notebook
This command will start the Jupyter server and open your default web browser to the notebook interface.
