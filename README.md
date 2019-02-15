# Improving the Input Accuracy of Touchscreens using Deep Learning
This repository contains the code as described in the CHI Late-Breaking Work '19 Paper on improving the input accuracy of touchscreens using deep learning. 

## Abstract
Touchscreens combine input and output in a single interface. While this enables an intuitive interaction and dynamic user interfaces, the fat-finger problem and the resulting occlusions still impact the input accuracy. Previous work presented approaches to improve the touch accuracy by involving visual features on the top side of fingers, as well as static compensation functions. While the former is not applicable on recent mobile devices as the top side of a finger cannot be tracked, compensation functions do not take properties such as finger angle into account. In this work, we present a data-driven approach to estimate the 2D touch position on commodity mutual capacitive touchscreens which increases the touch accuracy by 23.0% over recently implemented approaches.

## Notebooks
`_01_Data-Preprocessing.ipynb` contains code for reading in the data set and preprocessing it. It further contains code for plotting figures to demonstrate the offset between intended input position and the registered one by Android. 

`_02_Model-Training.ipynb` contains the code for reading in the preprocessed data, as well as the model definition and training with Keras. 
