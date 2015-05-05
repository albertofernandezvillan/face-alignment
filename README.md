# face-alignment

### Introduction
Alignment step of a face recognition algorithm is often ignored or not detailed. In some cases, the alignment is done manually, where the positions of the eyes are manually labeled. In other cases, this step is ignored, under the assumption that the face detection algorithm will perform some kind of alignment.

### Procedure
A face alignment and normalization algorithm is proposed. In order to get the angle
of misalignment, a regression line is calculated based on four points: the canthi of the left and right eye, i.e., left inner eye, left outer eye, right inner eye and right
outer eye. After that, faces are rotated and aligned in the images so that eyes are located in the same coordinates for all the images.

For more information, you can see this post on opencv Q&A:
http://answers.opencv.org/question/24670/how-can-i-align-face-images/

This code is part of the project 'Glasses detection on real images based on robust alignment'.



### Citation
If you use the provided code for your work, please cite the following paper:

Fernández, A., García, R., Usamentiaga, R., & Casado, R. (2015).**Glasses detection on real images based on robust alignment**. Machine Vision and Applications, 1-13.

http://link.springer.com/article/10.1007/s00138-015-0674-1

This Readme file is created with http://prose.io 









