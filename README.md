# DeCloud-GAN
Optical Remote Sensing imagery has several applications in monitoring the states of natural and man-made features around the globe. However, due to clouds and other climatic conditions, information extracted from the imagery retrieved is very limited.

Deep learning has often been used in several image processing and remote sensing tasks. <br> 
In this work, we propose the usage of generative adversarial networks to remove clouds and other climatic interference from high-resolution remote sensing imagery.

We have trained and tested upon the Remote sensing Image Cloud rEmoving dataset (RICE). The novel network(DeCloud GAN) we propose, makes use of residual UNets and pixel shuffle layers in the generator, which yield high quality cloudless satellite images. We have tested 4 methods for comparison, and have found that DeCloudGAN achieves the best performance on two main metrics, peak signal to noise ratio (PSNR) and structural similarity index (SSIM), to measure similarity in visual perception of the produced
and target images.


If this work has been useful to you, please do cite this paper published with ACM: <br>
@inproceedings{10.1145/3507623.3507628, <br>
author = {Bhambani, Krisha and Takalikar, Mukta}, <br>
title = {DeCloud GAN: An Advanced Generative Adversarial Network for Removing Cloud Cover in Optical Remote Sensing Imagery}, <br>
year = {2021}, <br>
isbn = {9781450385930}, <br>
publisher = {Association for Computing Machinery}, <br>
address = {New York, NY, USA}, <br>
url = {https://doi.org/10.1145/3507623.3507628}, <br>
doi = {10.1145/3507623.3507628}, <br>
booktitle = {2021 The 4th International Conference on Computational Intelligence and Intelligent Systems}, <br>
pages = {25–30}, <br>
location = {Tokyo, Japan}, <br>
series = {CIIS 2021} <br>
}
