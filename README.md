# Human-shape estimation with artificial backgrounds
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
 Human Body Dimension (HBD) Estimation using
images becomes increasingly important. Datasets consisting of
images of synthetically created human body meshes have been
successfully used for training convolutional neural networks
(CNN) to estimate HBDs. However, those images all have
a uniform grey background which is rather improbable in
practical application. But adding an artificial background to the
image might make it harder to clearly identify the human shape.
In this work, we introduce uniformly colored and textured
background into an existing dataset of images of human body
meshes. We develop and train an existing network architecture
and then let it predict the HBDs. Our modified network
achieved better results (∼50% less relative percentage error)
than those reported in the original work we focused on. And it
even accomplish remarkable results with different backgrounds.

## our semester paper
[LINK](https://github.com/nerovalerius/humanoids_cnn/blob/main/human_shape_classification_w_backgrounds.pdf)

## original paper
[LINK](https://github.com/neoglez/neural-anthropometer)

## results
![results psp](https://github.com/nerovalerius/humanoids_cnn/blob/main/results.jpg)

