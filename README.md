# Frequency Vision Lab

Simple experiments for image processing using frequency-domain transforms.

## Topics

- FFT / IFFT
- DCT / IDCT
- Frequency filtering
- Image enhancement
- Noise and detail analysis

## Environment Setup

This project uses a Python virtual environment (`venv`) with Jupyter Notebook.

## Goal


The purpose of this repository is to compare FFT and DCT based image processing methods and evaluate their usefulness for image enhancement and frequency analysis.

## Create Virtual Environment

From the project root directory:


```
python -m venv .venv
```

```
.\.venv\Scripts\Activate.ps1
```

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

## Run Jupyter Notebook

* Test with Jupyter Notebook           
  * [notebooks/01](./notebooks/01_fft_dct_basics.ipynb)
  * [notebooks/02](./notebooks/02_fft_dct_filters.ipynb)


## Reference

- Fourier Transforms in Python  
  https://raghavchhetri.github.io/scattered.dimes/2021/07/21/Fourier-Transforms-in-Python

- PHY Simuation and RF Mixer   
  https://github.com/JeonghunLee/phy_simulation
