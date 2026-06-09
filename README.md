# DAIC-WOZ OpenWillis Pipeline
Acoustic feature extraction and exploratory depression analysis using the DAIC-WOZ dataset and OpenWillis.

## Project Overview
This project demonstrates a reproducible workflow for extracting acoustic speech features from clinical interview recordings and exploring their relationship with depression severity scores.

The pipeline uses:

- DAIC-WOZ interview recordings
- OpenWillis acoustic feature extraction
- Python-based preprocessing and analysis
- Jupyter Notebook for reproducibility

The primary goal is to investigate whether speech-derived acoustic features can provide useful information for depression assessment.

## Dataset
This project uses the Distress Analysis Interview Corpus – Wizard of Oz (DAIC-WOZ).

**Reference:**

Jonathan Gratch, Ron Artstein, Gale Lucas, Giota Stratou, Stefan Scherer, Angela Nazarian, Rachel Wood, Jill Boberg, David DeVault, Stacy Marsella, David Traum, Skip Rizzo, Louis-Philippe Morency, “The Distress Analysis Interview Corpus of Human and Computer Interviews,” in Proceedings of Language Resources and Evaluation Conference (LREC), 2014.

## Workflow
1. Load DAIC-WOZ audio recordings
2. Extract acoustic features using OpenWillis
3. Create a participant-level feature table
4. Merge extracted features with depression labels
5. Perform exploratory analysis and visualization
6. Train baseline machine learning models

## Disclaimer
This repository is intended for research and educational purposes only.
