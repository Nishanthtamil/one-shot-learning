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

