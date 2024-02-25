# Markov Chain Composer in Python
Welcome to the Markov Chain Composer project in Python! This repository contains a Python implementation of a Markov chain-based music composer. The Markov Chain Composer generates musical sequences based on input MIDI files using Markov chain models, allowing users to create new musical compositions inspired by existing melodies.

## Features
1. **Input MIDI Files:** Accepts MIDI files as input, containing musical sequences to be used as the basis for generating new compositions.

2. **Markov Chain Modeling:** Analyzes the input MIDI files and builds Markov chain models to capture the statistical relationships between musical elements such as notes, chords, and rhythms.

3. **Music Generation:** Generates new musical sequences by traversing the Markov chain models and selecting sequences of musical elements based on their probabilities.

4. **Customizable Parameters:** Allows users to customize various parameters such as the order of the Markov chain, the length of generated sequences, and the musical style.

5. **Output MIDI Files:** Outputs generated musical sequences as MIDI files, which can be played using MIDI-compatible software or devices.

## Installation
To use the Markov Chain Composer, follow these steps:

1. **Clone the Repository:** Clone the repository to your local machine using the following command:

git clone https://github.com/RadinaAvramova/graph-composer.git

2. **Navigate to the Directory:** Change your current directory to the location of the cloned repository:

cd graph-composer

3. **Install Dependencies:** Install the required dependencies using pip:

pip install -r requirements.txt

## Usage
1. **Prepare MIDI Files:** Gather MIDI files containing musical sequences that you want to use as input for the composer.

2. **Run the Composer:** Execute the Python script to run the Markov Chain Composer:

python markov_chain_composer.py --input_path path_to_input_files --output_path path_to_output_files

3. **Specify Parameters:** Optionally, specify parameters such as the order of the Markov chain, the length of generated sequences, and other customization options.

4. **Generate Music:** Let the composer analyze the input MIDI files and generate new musical sequences based on the Markov chain models.

5. **Review Output:** Review the generated MIDI files in the specified output directory and listen to the new compositions using MIDI-compatible software or devices.

## Customization
1. **Model Order:** Adjust the order of the Markov chain to capture different levels of musical structure and complexity.

2. **Sequence Length:** Modify the length of generated musical sequences to create shorter or longer compositions.

3. **Musical Style:** Experiment with different input MIDI files representing various musical styles and genres to influence the generated compositions.

4. **Model Training:** Explore different methods for training Markov chain models, such as using different algorithms or incorporating additional features.
