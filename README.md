
# Image Colorization -- LAB to RGB
## Convolutional Neural Nets, Autoencoders, and Generative Adversarial Networks

### Client: Florida Memory, the digital outreach program of the State Archives of Florida.
## Background: Florida Memory digitizes thousands of black and white photos a year for the State Archives. These images already enjoy success with the State Museum, and statewide historical organizations.

### Mission: Produce a model that can successfully colorize black and white photos, without a reduction to quality.
### Goal: Increase outreach, generate renewed interest in the program.

If a successful colorization model can be achieved, then a model for semantic segmentation (object detection), would also be welcome, as it would facilitate the Archives' ability to classify their own inventory; this, in turn, would increase the historic integrity of the materials.

## Dataset: https://www.kaggle.com/shravankumar9892/image-colorization

25 thousand photos, split along their L and AB channels, respectively. Kept in the .npy format.

# Convolutional Neural Network

### Step 1: Baseline CNN -- fully connected layers, with and without upsampling, pooling, etc.
### Step 2: Adapted CNN -- Keras' ImageDataGenerator for greater feature mapping; deeper learning.

# Autoencoding

### Step 1: ImageDataGenerator, AB channel normalzing, baseline results

# Generative Adversarial Network

### Outline: Work in progress. Goal model for most faithful recolorizations.

# Recommendations:

### Internal: Custom datasets adhering to the best images Florida Memory has to offer, in the most up-to-date file formats. Blogging to generate interest and support.

### External (for the Data Scientist): More research into the pros/cons/potential of Autoencoders; then, a fully fledged Generative Adversarial Network. Afterwards, object detection/classification, and then portability either as a web service or API.

