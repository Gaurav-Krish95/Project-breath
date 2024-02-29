# Project-breath: Recording and Analyzing Environmental Noise for Breathing Detection

## Introduction
Project-breath is a mini-project aimed at detecting breathing patterns using a simple setup involving a smartphone with an JBL C200si earphone mic. By recording environmental noise and analyzing the frequency spectrum, we can distinguish between breathing and non-breathing sounds.

## Setup
- *Hardware*: moto g71 with an JBL earphone mic.
- *Software*: Lexis Audio Editor, AudioAudacity (for filtering and plotting)

## Methodology
1. *Recording*: Use the earphone mic to record breathing & environmental noise.
2. *Pre-processing*: Import the audio into Audacity and apply a high-pass filter to remove higher frequencies.
3. *Analysis*: Plotted a spectrogram in audacity to visualize the frequency content of the recorded audio.
4. *Frequency Range Identification*: Identify the frequency range associated with breathing and non-breathing sounds.
5. *Detection*: Utilize the identified frequency range to detect breathing patterns.

## Dependencies
- Audacity
  
## Usage
1. *Recording*: Use the provided script to record environmental noise.
2. *Pre-processing*: Import the recorded audio into Audacity and apply a high-pass filter with a cutoff frequency to remove unwanted noise.
3. *Analysis*: Run the Python script to plot the spectrogram and identify the frequency range associated with breathing.
4. *Detection*: Implement the breathing detection algorithm using the identified frequency range.

# Load audio data
# Perform Fourier Transform
# Plot spectrogram
# Identify breathing frequency range


## Future Work
- Real-time detection implementation.
- Integration with wearable devices for continuous monitoring.
- Enhancement of detection algorithm for accuracy and robustness.
## Contributors
- [Gaurav](https://github.com/Gaurav-Krish95)

