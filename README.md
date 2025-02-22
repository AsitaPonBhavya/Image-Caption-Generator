# Image Caption Generator - CNN + LSTM

This project implements an **Image Caption Generator** using a **CNN-LSTM** model. It extracts image features using **VGG16** and generates captions using an **LSTM-based sequence model**. The model is trained on image-caption datasets to produce descriptive text for input images.

## Features
- Extracts image features using a **pretrained VGG16 model**.
- Processes textual descriptions using an **LSTM-based language model**.
- Generates captions using **beam search decoding**.
- Supports custom image testing and visualization.

## Technologies Used
- Python, TensorFlow, Keras
- VGG16 for CNN-based feature extraction
- LSTM for text sequence modeling
- NumPy, Pandas for data processing
- Matplotlib for visualization
- tqdm for progress tracking

## Installation
Clone the repository:
```bash
git clone https://github.com/your-username/image-caption-generator.git
cd image-caption-generator
