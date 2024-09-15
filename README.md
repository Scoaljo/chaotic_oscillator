# Chaos Theory Sound Generator

This project generates unique sounds based on the logistic map, a simple mathematical model that exhibits chaotic behavior. Each run of the script produces a different "melody" that audibly represents chaos theory in action, demonstrating how small changes in initial conditions can lead to vastly different outcomes.

## Project Overview

The goal of this project is to create an audible representation of chaos theory using the logistic map equation. We use Python to generate chaotic sequences and convert them into unique melodies, providing both audio and visual outputs for each run.

## Key Features

- Generation of unique chaotic sequences
- Conversion of chaotic sequences into audible melodies
- Visualization of the logistic map and chaotic sequence
- Unique file naming for each run's outputs

## Experiments

The project allows for various experiments by modifying key parameters:

- **Initial Condition**: Each run uses a different random initial value (x0).
- **Frequency Mapping**: The chaotic sequence is mapped to a range of frequencies.
- **Tone Duration**: Each value in the sequence is converted to a short tone.
- **Visualization**: The logistic map and chaotic sequence are plotted for each run.

## Results

The project demonstrates key principles of chaos theory:

- Small changes in initial conditions lead to significantly different melodies.
- The visualizations show the unpredictable nature of the chaotic sequence.
- Each run produces a unique auditory and visual representation of chaos.

## Technologies Used

- Python
- NumPy
- Matplotlib
- SciPy

## Usage

1. Install required packages:
pip install numpy matplotlib scipy
2. Run the script:
python chaotic_oscillator.py
3. The script generates:
- A WAV file with a unique chaotic melody
- A PNG file visualizing the logistic map and chaotic sequence
- Console output showing the initial value and first few terms of the sequence

## Contributing

Contributions to this project are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.
