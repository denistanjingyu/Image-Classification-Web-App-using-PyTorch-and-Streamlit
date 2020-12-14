# Image Classification Web App

![image](https://user-images.githubusercontent.com/45563371/102043522-97f85d00-3e0f-11eb-924e-e98b46fa074a.png)

## Overview
A simple web demo with minimal framework using PyTorch and Streamlit to showcase an image classification model

## Steps to Use the Application
- Clone the repository onto your own local machine
- Open command prompt/terminal
- Run pip install -r requirements.txt
- Type ‘streamlit run steamlit_ui.py’ in the command prompt/terminal
- A localhost address should automatically open in your web browser. If not, copy the local URL from the command prompt/terminal into your web browser.
- Click 'Browse files' and upload an image file in jpg format
- Now just wait for the results. 5 predictions should be outputted from highest probability to lowest probability.

## Model Used
### ResNet-101
ResNet-101 is a convolutional neural network that is 101 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals.

## Installation
```
pip install -r requirements.txt
```

## Code and Resources Used
- Python: Version 3.7.4
- Packages: PIL, torchvision, torch, streamlit
