# Mask-Detection Project
* School project in Deep Learning For Computer Vision Course


# Project Goal
During these periods Covid 19 spreads rapidly, Wearing masks has become a big part of our lives.
Organizations and countries are looking for a way to track mask wearing using artificial intelligence.
The following project shows the feasibility of the solution and examines a number of different models and finally presents their results.



# Model Selection
* I used faster RCNN with different backbone - from smaller ones like mobileNet to vgg19 up to resNet 50.
* I tried resNet101 but Unfortunately, I couldn't load the model and the data to the GPU simultaneously. (At this projects I used 12gb memory GPU)


# Hyperparametes search

* Epochs number - 10 , 50 ,100
* Different learning rates: 0.01 - 0.0003.
* Different optimizers: Adam & SGD - with weight decay and momentum.


# Summary
At this project I examined a number of detection models, In order to identify and localize in pictures people who wear a mask, do not wear or do not wear it properly.

I started by building a dirty implementation in order to find the best hyperparameters tune.
The secoud stage was to do some experiments on larger and deeper detection models hopefully to get better results, and so it was.
