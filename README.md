# Convolutional Neural Networks and Training Strategies for Skin Detection (ICIP 2017)


<p align="center">
<img src="/docs/imagebasedcolor.png" width="700"> 
<img src="/docs/patch_based_color.png" width="700">
</p>

## Abstract

This paper presents two convolutional neural networks (CNN) and their 
training strategies for skin detection.
The first CNN consists
of 20 convolution layers with 3 x 3 filters
which is a kind of VGG network,
and the second is composed of 20 network-in-network (NiN)
layers, which can be considered a modification of
Inception structure.
When training these networks for human skin detection,
we consider patch-based and whole-image-based
training. The first method focuses on local features
such as skin color and texture, and the second on the
human-related shape features as well as color and texture.
Experiments show that the proposed CNNs yield
better performance than the conventional methods and
also than the existing deep-learning based method.
Also, it is found that the NiN structure generally shows
higher accuracy than the VGG-based structure. 
The experiments also show that the whole-image-based
training that learns the shape features 
yields better accuracy
than the patch-based learning that focuses 
on local color and texture only.

## All Experimental results on ECU, Pratheepan, and HGR dataset
### Proposed method
* Patch based VGG method
* Patch based NiN method
* Image based VGG method
* Image based NiN method


## Quantitative and Subjective Results 
<p align="center">
<img src="/docs/PRROCcurves.PNG" width="400">

<em>Comparison of PR and ROC curves</em>
</p>

<p align="center">
<img src="/docs/res1.PNG" width="500">

<em>Visual comparison with outher methods on the Pratheepan dataset</em>
</p>






