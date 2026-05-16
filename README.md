# EEG Frequency Band Classifier

A Python tool that classifies brain wave frequencies into standard 
neuroscience bands (delta, theta, alpha, beta, gamma).

## What it does
- Classifies a single frequency into its EEG band
- Classifies a list of frequencies
- Counts how many frequencies fall into each band

## Background
EEG (Electroencephalography) measures electrical activity in the brain.
Different frequency ranges correspond to different mental states.
This classifier uses the standard clinical band definitions.

## Usage
```python
from eeg_classifier import classify_frequency, band_counts

print(classify_frequency(10.0))  # alpha
print(band_counts([1.2, 5.5, 10.0, 22.0, 45.0]))
```

## Built with
Python · MNE-Python band definitions · MIT 6.0001 OCW knowledge

## Why this exists
Built as a mini project to apply Python fundamentals to real 
neuroscience data structures. Part of my open source learning path.
