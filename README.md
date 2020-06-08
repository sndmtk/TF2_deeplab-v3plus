# TF2_deeplab-v3plus
deeplab-v3plus semantic segmentation with tensorflow2.2 using frozen inference graph.

# Setup
First, create 'models' directory and place the downloaded [models](https://github.com/tensorflow/models/blob/master/research/deeplab/g3doc/model_zoo.md) in it.
 
This notebook uses [spout](https://spout.zeal.co/) library to exchange data with other tools (ex. TouchDesigner). If you're using python 3.7 on Windows, you can use the spout library that I built. Please download it from release page. Otherwise, you can build it yourself from [this project](https://github.com/AleDel/Spout-numpy).
