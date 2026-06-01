# neurocore

A Python package for EEG signal processing (built from scratch).

Reusable utilities extracted from my motor-intent-decoder project. The idea 
is that the core operations in an EEG pipeline (filtering, epoching, feature 
extraction) should be clean, well-documented functions anyone can use on 
their own data.

## planned modules
- `filter` — bandpass filtering for EEG frequency bands
- `epoch` — cutting continuous signals into labeled trial windows  
- `features` — CSP and other feature extraction methods
- `viz` — signal visualization utilities

## status
In active development — code arriving week 10 of summer 2026.
Built alongside motor-intent-decoder.

## why
I wanted to understand these operations from first principles before using 
a library that abstracts them away.
