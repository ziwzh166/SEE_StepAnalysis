# SEE_Step Analysis

This repository provides two distinct methods for step detection in the SEE experimental signal, each tailored to a specific use case: low sampling frequency and high sampling frequency. Each method is located in its respective folder.

## Repository Structure

Each folder contains:

- A script for running the step detection algorithm.
- An example data file.
- A trained model saved in `.keras` format.
- The corresponding training history saved in `.pkl` format.

## Requirements

To run the scripts, ensure the following Python packages are installed in your environment:

- numpy
- scipy
- pandas
- pywt
- TensorFlow
- plotly 

## Usage

The scripts are written in Jupyter notebook format. Please note that only CPU support is available. Running the script with the CNN section may take a considerable amount of time due to CPU limitations.