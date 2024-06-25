# HV2DrumSynth
This repository houses the source code for an audio classification model that identifies human beatboxing sounds.

# Project Overview:

The model takes a human voice input (e.g., beatboxing) and categorizes it into specific drum sounds like kick, snare, hi-hat open/closed. This allows users to create percussive sounds using their voice and opens doors for interactive music experiences.

# Technical Approach:

**Feature Engineering***: Audio samples are transformed into mel spectrograms, a visual representation of frequencies over time. This format provides a suitable input for Convolutional Neural Networks (CNNs) to learn patterns.

**Model Architecture**: The HV2DrumSynth-Model_Creation script utilizes the Keras library to build and train a CNN model specifically designed for audio classification.

**Training & Validation**: The HV2DrumSynth-Model_Creation script also handles training the model on a labeled dataset of human beatboxing sounds. It evaluates the model's performance through validation techniques.

# Repository Structure:

**HV2DrumSynth-DSP_and_Image_Generation.ipynb**: This script focuses on Exploratory Data Analysis (EDA) and preprocessing the audio data. It transforms audio clips into mel spectrograms for feeding into the CNN model.

**HV2DrumSynth-Model_Creation_and_Validation.ipynb**: This script tackles building the CNN model architecture using Keras. It then trains the model on the prepared data and analyzes its performance through validation metrics.

# Project Highlights

* The validation accuracy for the best model is ~ 91%
* Testing & outputs for this application are still under development, stay tuned :)

