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



```python
from ultralytics import YOLO
