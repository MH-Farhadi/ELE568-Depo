# EEG Signal Quality Analysis Tool

A Python-based tool for evaluating EEG signal quality across different electrode types and saline concentrations.

## Overview

This tool analyzes EEG signals to determine which electrode configuration produces the highest quality recordings. It evaluates:

- Artifact presence (spikes, flat signals, muscle artifacts, line noise)
- Signal quality metrics (SNR, spectral characteristics, stability)
- Estimated electrode impedance
- Overall signal quality score

## Usage

1. Place your EEG data files in the `/data` folder
2. Name files according to configuration: `{electrode_type}_{saline_concentration}.csv`
3. Run the analysis: `python eeg_quality_analysis.py`
4. Results will be saved in the `/results` folder

## Features

- Comprehensive artifact detection
- Advanced signal quality metrics
- Automated comparison across configurations
- Visualization of key quality parameters
- Test data generation for validation

## Requirements

- Python 3.6+
- NumPy
- Pandas
- Matplotlib
- MNE-Python
- SciPy

## Installation

```bash
pip install numpy pandas matplotlib mne scipy
