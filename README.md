# Ancient Character Recognition with One-Shot Learning

## Overview
This project implements a character recognition system using one-shot learning. The model is trained to recognize new characters with minimal data, leveraging a pre-trained CNN model adapted for this purpose. The data for this project is sourced from temple manuscripts, specifically "kalvettu" (stone inscriptions).

## One-Shot Learning
The model uses a Siamese network, which consists of two identical sub-networks sharing the same parameters. This architecture is particularly effective for one-shot learning tasks, where the goal is to recognize new characters with only a single example.

## Usage

### Prerequisites
- Python 3.x
- TensorFlow
- NumPy

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Nishanthtamil/one-shot-learning.git
2. Requirements:
   ```bash
   pip install -r requirements.txt
### Preparing One-Shot Data:
The prepare_one_shot_data_for_new_classes function prepares the data for one-shot learning. Replace the placeholder image data and labels with actual data.

### Loading the Pre-Trained Model:
To load the pre-trained CNN model, follow the instructions provided in the Jupyter notebook.

### Training the Siamese Model:
1.Load your pre-trained CNN model and freeze its layers.
2.Define the Siamese network architecture.
3.Compile the Siamese model with the contrastive loss function.
4.Train the model with one-shot data as detailed in the Jupyter notebook.
### Recognizing New Characters:
1.Load and preprocess the new image.
2.Compare the new image with known images to get similarity scores as detailed in the Jupyter notebook.
### Evaluation:
Evaluate the fine-tuned Siamese model as detailed in the Jupyter notebook.

## Results:
Include some examples and performance metrics here to showcase the effectiveness of your model.

## License:
This project is licensed under the MIT License - see the LICENSE file for details.
