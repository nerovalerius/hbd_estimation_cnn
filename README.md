# humanoids_cnn
Detect Humans / Monsters with a CNN

This repository aims to train a convolutional neural network with generated images of humans and monsters.
The dataset is annotated with human body dimension. Monsters have dimensions which are "unnatural".

The images have a grey background. We first introduce artificial backgrounds to the dataset.
Three datasets are then created:
* the original dataset with a grey background
* the humanoids with a texture background 
* the humanoids with a random single color RGB background

The goal is to detect the humanoids and be able to calculate their body dimensions.
Monsters and humans should be differentiated.
