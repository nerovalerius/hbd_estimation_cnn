# Human-shape classification with artificial backgrounds
## Armin Niedermueller and Melanie Urban

This repository aims to train a convolutional neural network with generated images of humans and monsters.
The dataset is annotated with human body dimension. Monsters have dimensions which are "unnatural".

The images have a grey background. We first introduce artificial backgrounds to the dataset.
Three datasets are then created:
* the original dataset with a grey background
* the humanoids with a texture background 
* the humanoids with a random single color RGB background

The goal is to detect the humanoids and be able to calculate their body dimensions.
Monsters and humans should be differentiated.

## Abstract: 
Human Body Dimensions (HBD) Estimation using
images becomes increasingly important. Datasets consisting of
2d images of humanoids have been successfully generated and
then used for training such networks. However, those images all
have a single coloured grey background. The HBD estimation
of such images generates very good results, but what if an
artificial background is introduced into the dataset and the
humans are visually not easily separable? In this work, we
introduce random coloured backgrounds as well as textured
backgrounds into an existing dataset of humanoids. We create
and train a modified network architecture and then calculated
the HBDs. Our modified network achieved far better results
(~ 50% improvement) as in the original paper, even with the
texture and background dataset.

## our semester paper
[LINK](https://github.com/nerovalerius/humanoids_cnn/blob/main/human_shape_classification_w_backgrounds.pdf)

## original paper
[LINK](https://github.com/neoglez/neural-anthropometer)

## results
![results psp](https://github.com/nerovalerius/humanoids_cnn/blob/main/results.jpg)

