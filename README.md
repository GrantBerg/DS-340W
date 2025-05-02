# DS340W Final Project: Chord Extraction for Symbolic Music Generation 

## Project Description
This project analyzes musical sequences from the Wikifonia dataset using an N-gram language model. It compares the perplexity of raw note sequences versus chordified sequences (condensed into chords using `music21`).

## Dataset
The [Wikifonia dataset](http://www.synthzone.com/files/Wikifonia/) will be automatically downloaded and extracted when running the notebook (via the `muspy` library). The dataset contains lead sheets in `.mxl` format.

## Requirements
- Python 3.x
- Libraries (automatically installed in the notebook):
  - `muspy`
  - `music21`
  - `miditoolkit`
  - `pretty-midi`
  - Other dependencies (see notebook)

## Usage
1. Run the Jupyter notebook `DS340w_final_project_code.ipynb` sequentially.
2. By default, the notebook uses a **random 50-file subset** of Wikifonia for faster testing.
3. Outputs include:
   - Perplexity scores for raw note sequences vs. chord sequences.


