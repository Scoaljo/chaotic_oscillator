# Chaos Theory Sound Generator

Generate unique melodies based on the logistic map, a simple mathematical model that exhibits chaotic behavior. Each run produces a different audio representation of chaos theory in action.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Features

- 🎵 Generates a unique chaotic sequence each run
- 🔊 Converts chaotic sequences into audible "melodies"
- 📊 Produces visualizations of the logistic map and chaotic sequence
- 💾 Saves audio files and visualizations with unique names

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- SciPy

## Installation

1. Clone this repository:
git clone https://github.com/yourusername/chaos-theory-sound-generator.git
cd chaos-theory-sound-generator
Copy
2. Install the required packages:
pip install numpy matplotlib scipy
Copy
## Usage

Run the script:
python chaotic_oscillator.py
Copy
The script generates:
- A WAV file containing a unique chaotic melody
- A PNG file visualizing the logistic map and chaotic sequence
- Console output showing the initial value and first few terms of the sequence

## How It Works

- Uses the logistic map equation: x[n+1] = rx[n](1-x[n])
- Chooses a random initial value (x0) each run
- Maps the resulting chaotic sequence to frequencies, creating a series of tones
- Demonstrates the butterfly effect - small changes in initial conditions lead to vastly different outcomes

## Customization

Modify parameters like `duration`, `sample_rate`, and frequency range in the script to experiment with different sounds.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.