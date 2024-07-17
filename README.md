# object-detection-onnx-inference

The main focus of this project would be to showcase the steps involved in inference of an ONNX-based object detection model. 
### Required input: 
data_images.zip

yolo_weight.onnx.zip

### Expected output:
onnx_output.csv

### The content of the project could include the following:
1. [Introduction to ONNX](#1-introduction-to-onnx)
2. [Setting up the Environment](#2-setting-up-the-environment)
3. [Preprocessing the Input Image](#3-preprocessing-the-input-image)
4. [Running the Inference](#4-running-the-inference)

<html itemscope itemtype="https://schema.org/FAQPage">
  <div itemscope itemprop="mainEntity" itemtype="https://schema.org/Question">
    <a id="1-introduction-to-onnx"><h2 itemprop="name"> 1. Introduction to ONNX</h2></a>
    <div itemscope itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
      <div itemprop="text">
[ONNX, the Open Neural Network eXchange](https://onnx.ai/), is an open format and standard built to represent machine learning models.The goal of ONNX is to provide a unified way to represent deep learning models, allowing them to be easily transferred and deployed across different platforms and ecosystems.
If you want to get to know more of how is the onnx architecture is you can access to [netron](https://netron.app/)

<html itemscope itemtype="https://schema.org/FAQPage">
  <div itemscope itemprop="mainEntity" itemtype="https://schema.org/Question">
    <a id="2-setting-up-the-environment"><h2 itemprop="name"> 2. Setting up the Environment</h2></a>
    <div itemscope itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
      <div itemprop="text">
        
```python
        
!pip install onnxruntime
!pip install onnx

```




## Usage procedures 
## Reference 
