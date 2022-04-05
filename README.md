# Food Classification Using Efficientnet model by transferlearning

## 1.Problem Statement
> How well can we predict from this huge Food dataset, can it predict the 101 classes for different kind of food ?

## 2.Data
> The Food101 came from tensorflow Datasets, which is ready to use in "tensors" form. But the original it's from : Food-101 – Mining Discriminative Components with Random Forests paper and their respected authors {Bossard, Lukas and Guillaumin, Matthieu and Van Gool, Luc} src:https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/

## 3.Evaluation
> if this model can reach accuracy above 90% of food classification form the 101 classes, then this project will pursue its improvements.


## 4.Features
> This dataset consists of 101 food categories, with 101'000 images. For each class, 250 manually reviewed test images are provided as well as 750 training images. On purpose, the training images were not cleaned, and thus still contain some amount of noise. This comes mostly in the form of intense colors and sometimes wrong labels. All images were rescaled to have a maximum side length of 512 pixels.
- images with different width, height such as: (512, 512, 3), the color channel is 3 doesn't change.
- label: contains mix of numbers(the label number in index) and the name of the label.

for further info:https://www.tensorflow.org/datasets/catalog/food101

