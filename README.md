# Hiragana Image Generation

This project focuses on generating images of Japanese Hiragana characters using a Convolutional Neural Network (CNN) implemented with PyTorch. The core implementation is provided in the Jupyter Notebook [`main.ipynb`](https://github.com/iScape4code/Hiragana-Image-Generation/blob/main/main.ipynb).

## Overview

The notebook demonstrates the complete workflow for Hiragana image generation:

- **Data Loading & Preprocessing**: Reads the dataset of Hiragana character images, applies resizing and normalization.
- **Model Definition**: Defines a simple CNN architecture with convolutional, pooling, and fully connected layers.
- **Training Loop**: Trains the CNN on the preprocessed data, showing loss and accuracy metrics.
- **Image Generation**: Uses the trained model to generate and save new Hiragana character images.
- **Visualization**: Displays sample generated images and training curves.

## Repository Structure

```
├── main.ipynb           # Jupyter Notebook with end-to-end implementation  
├── data/                # (Optional) Directory for raw/generated datasets  
├── models/              # Saved model checkpoints  
├── outputs/             # Generated images and plots  
├── requirements.txt     # Project dependencies  
└── README.md            # This file  
```

## Prerequisites

- **Python**: 3.7 or higher  
- **Jupyter Notebook**: To run and modify `main.ipynb`  
- **Libraries**: Listed in `requirements.txt`, including:
  - `torch`
  - `torchvision`
  - `numpy`
  - `matplotlib`

## Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/iScape4code/Hiragana-Image-Generation.git
   cd Hiragana-Image-Generation
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**  
   ```bash
   jupyter notebook
   ```
   Then open and run `main.ipynb`.

## Usage

1. **Data Preparation**  
   - Place your raw Hiragana images in `data/raw/` (if using a custom dataset).  
   - The notebook will automatically split and preprocess them.

2. **Model Training**  
   - Execute the training cells in `main.ipynb`.  
   - Checkpoints will be saved to `models/`.

3. **Image Generation & Visualization**  
   - Run the generation cells to produce new Hiragana images.  
   - Outputs are saved in `outputs/` and displayed inline.

## Results

After training, you will find:

- **Trained Model** in `models/`  
- **Generated Samples** in `outputs/generated_images/`  
- **Training Curves** in `outputs/plots/`

Open the notebook to view sample images and performance graphs.

