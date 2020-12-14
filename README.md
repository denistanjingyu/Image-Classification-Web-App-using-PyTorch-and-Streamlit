# Image Classification Web App

![image](https://user-images.githubusercontent.com/45563371/102043522-97f85d00-3e0f-11eb-924e-e98b46fa074a.png)

Table of Contents :bookmark_tabs:
=================
- [Overview](#overview)
- [Steps to Use the Application](#steps-to-Use-the-application)
- [Model Used](#model-used)
- [Installation](#installation)
- [Code and Resources Used](#code-and-resources-used)

## Overview
A simple web demo with minimal framework using PyTorch and Streamlit to showcase an image classification model

## Steps to Use the Application
- Clone the repository onto your own local machine

![image](https://user-images.githubusercontent.com/45563371/102073488-58953500-3e3e-11eb-9581-e16823f808fd.png)

- Open command prompt/terminal

![image](https://user-images.githubusercontent.com/45563371/102073585-7b274e00-3e3e-11eb-8656-a67df96b995a.png)

- Run pip install -r requirements.txt

![image](https://user-images.githubusercontent.com/45563371/102073729-af9b0a00-3e3e-11eb-95f4-d02d01b6fa76.png)

- Type ‘streamlit run steamlit_ui.py’ in the command prompt/terminal

- A localhost address should automatically open in your web browser. If not, copy the local URL from the command prompt/terminal into your web browser.

![image](https://user-images.githubusercontent.com/45563371/102073842-dbb68b00-3e3e-11eb-8e7e-0f67e0021b38.png)

- Click 'Browse files' and upload an image file in jpg format

![image](https://user-images.githubusercontent.com/45563371/102073949-056fb200-3e3f-11eb-9017-27bf13d3e88d.png)

![image](https://user-images.githubusercontent.com/45563371/102074070-289a6180-3e3f-11eb-8876-75ea60068ff2.png)

- Now just wait for the results. 5 predictions should be outputted from highest probability to lowest probability.

![image](https://user-images.githubusercontent.com/45563371/102074131-44056c80-3e3f-11eb-8d7d-093e6a5eed1d.png)

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
