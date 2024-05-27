Poker Hand Detection System

## Overview
This project is designed to detect the rank and suit of playing cards in images using a YOLO (You Only Look Once) model. By training the model with images from Roboflow Universe, it can accurately recognize various card types such as Royal Flush, Flush, or Straight when presented with a set of five cards. Additionally, an algorithm has been developed to determine the type of poker hand formed by these cards.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Anurag99778/Poker-hand
    ```

2. Install the Ultralytics package:
    ```sh
    pip install ultralytics
    ```

## Training the Model

To train the YOLOv8 model, follow these steps:

1. Import YOLO from Ultralytics:
    ```python
    from ultralytics import YOLO
    ```

2. Ru Make sure to replace the `data.yaml` path with the path to your dataset configuration file.
By running these commands, you will obtain a `.pt` file, which is the trained model that you can use for running the PPE detection program.

## Usage

Once you have the trained model (`.pt` file), you can use it to detect PPE kits in images.

Here is an example of how to use the trained model to make predictions:

```python
from ultralytics import YOLO

# Load the trained model
model = YOLO('path/to/your/trained-model.pt')
