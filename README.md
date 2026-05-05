# LightCNN Image Classifier (Web Deployment)

This project is a browser-based image classifier built using a Lightweight CNN (LightCNN) model trained on the STL-10 dataset. The model is exported to ONNX format and runs entirely in the browser using ONNX Runtime Web, with no backend required.

## Features

- Image classification directly in the browser
- No server-side inference required
- ONNX model integration with JavaScript
- Local or hosted deployment (GitHub Pages, Netlify, etc.)
- Simple and responsive user interface
- Displays predicted class and confidence score

## Model Details

- Architecture: LightCNN with residual blocks and attention mechanisms
- Dataset: STL-10 (10 classes)
- Input size: 96 x 96 RGB images
- Output: 10 class probabilities (softmax)
- Framework: PyTorch (training), ONNX (deployment)

## Classes

- airplane  
- bird  
- car  
- cat  
- deer  
- dog  
- horse  
- monkey  
- ship  
- truck  

## Project Structure
