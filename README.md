# Mask-Detection Project
* School project in Deep Learning For Computer Vision Course


# Project Goal
During these periods Covid 19 spreads rapidly, Wearing masks has become a big part of our lives.
Organizations and countries are looking for a way to track mask wearing using artificial intelligence.
The following project shows the feasibility of the solution and examines a number of different models and finally presents their results.


---
# Model Selection
faster RCNN with different backbone - from smaller ones like mobileNet to vgg19 to resNet 50.
I tried resNet101 but Unfortunately, we couldn't load the model and the data to the GPU simultaneously. ( At this projects i used 12gb memo GPU)

---
# Hyperparametes search
we did some testing with..
Epochs number - 10 , 50 ,100
Different learning rates: 0.01 - 0.0003.
Different optimizers: Adam & SGD - with weight decay and momentum.

---
# Summary
At this project I examined a number of detection models, In order to identify and localize in the pictures people who wear a mask, do not wear or do not wear properly.

I started by building a dirty implementation in order to find the best hyperparameters tune and then ran them on larger and deeper models and hopefully get better results, so it was.
