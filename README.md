# Unity Sentis - Digit Classification Project

## Overview
This project demonstrates digit classification using Unity Sentis, Unity's deep learning framework. It loads a trained neural network model, processes image inputs, and classifies handwritten digits in real-time.

## Features
- Utilizes Unity Sentis for deep learning inference.
- Loads a pre-trained digit classification model (e.g., an ONNX-based neural network).
- Processes input images and classifies digits with high accuracy.
- Displays classification results with probability scores.

## Requirements
- Unity 2022 or later
- Unity Sentis package installed
- ONNX model for digit classification (trained on MNIST or similar dataset)
- Basic knowledge of C# and Unity scripting

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/unity-sentis-digit-classification.git
   ```
2. Open the project in Unity.
3. Install the Unity Sentis package via the Package Manager if not already installed.
4. Place the pre-trained ONNX model into the **Assets/Models/** directory.
5. Ensure necessary scripts are attached to the Unity GameObjects.

## Usage
1. Run the Unity scene.
2. Provide an input image (e.g., a handwritten digit).
3. The model classifies the digit and displays the result on the UI.
4. View probability scores for each possible digit.

## Model Performance
- Achieved **87%** accuracy in test cases.
- Uses Softmax output to determine classification probabilities.

## Customization
- Replace the ONNX model with a different trained model for improved results.
- Modify the UI to enhance visualization of predictions.
- Extend the system to classify different types of handwritten symbols or datasets.

## License
This project is licensed under the MIT License.

## Contributors
- Shifa Ali

## Acknowledgments
- Unity Sentis documentation
- MNIST dataset for digit recognition
- ONNX for model compatibility with Unity Sentis

