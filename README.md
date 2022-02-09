# <center> :blowfish: :shark: MVA_DL_TrashDetection :whale: :octopus: </center>
Project for the Deep Learning course by Solène Blasco-Lopez and [Khaled Larbi](https://github.com/khaledlarbi)

This repository contains all the material from our Deep Learning project.

# Presentation of our project !

Our mission : Detect trashes on picture taken underwater. 

How ? By using deep learning. 
We will compare two kind of methods :

- [Faster RCNN](https://arxiv.org/pdf/1506.01497.pdf) : 2015 / The youngest from the RCNN gang / State-of-the art when he was younger
- [DETR](https://arxiv.org/pdf/1506.01497.pdf) : 2020 / [Attention](https://arxiv.org/pdf/1706.03762.pdf) : it's based on Transformers.

:abacus: Our dataset :abacus: : TrashCan dataset. This dataset was introduced on 2020 in the [paper](https://arxiv.org/pdf/2007.08097.pdf), and contains images from a submarine robot, with annotations for object detection and segmentation. We have chose to work on the 'instances' classes, that is to say on $22$ classes, including the robot that partly appears on many images, different trash categories, but also general categories of undersea fauna and flora.

![](https://conservancy.umn.edu/bitstream/handle/11299/214865/trash_can_thumbnail.jpg?sequence=8&isAllowed=y)

# Organisation of this repository !