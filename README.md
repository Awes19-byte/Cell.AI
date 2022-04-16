# MalariaCLass
Binary Image Classification with **Tensorflow** and **EfficientNetB0** pre-trained model <br>
And an other copy with **Tensorflow** and **ResNet50** pre-trained model <br> 
This repo is a binary classification project that identify cells images as **_parasitized_** or **_uninfected_** cells from the thin blood smear slide images of segmented cells.<br>
## Prerequisites 
`Python 3.x`
`Tensorflow 2.x`
## Datasets<br>
The Malaria dataset contains a total of 27,558 cell images with equal instances of parasitized and uninfected<br>
size:337.08 MiB<br>
On Tensorflow Datasets Catalog:[Malaria](https://www.tensorflow.org/datasets/catalog/malaria)<br>
The National Library of medecin:[NLM](https://lhncbc.nlm.nih.gov/LHC-publications/pubs/MalariaDatasets.html)<br>
# Model <br>
**EfficientNetB0** pre-trained model with 5,330,571	parameters<br>
its size: 29 MB  <br>
[Documentation](https://keras.io/api/applications/efficientnet/#efficientnetb0-function)<br>
**ResNet50** pre-trained model with 25,636,712	parameters<br>
its size: 98 MB  <br>
[Documentation](https://keras.io/api/applications/resnet/#resnet50-function)<br>
#Cells Segmentation
Cells segmentation with **detectron2** and **Mask R-CNN**
[Detectron2](https://github.com/facebookresearch/detectron2) 
