# FashionMNIST
a Neural Network project for FashionMNIST classification 
Just open the Jupyter notebook and Run. If you use RTX 4090D(24GB) * 2 for training, it would takes you about 2 hours to get all of the results.
In the Jupyter notebook, there are 4 different models, they are: Self designed Basic CNN(3 layers), Self designed Improved CNN(5 layers), transfer model ResNet50, transfer model MobileNetV2. I unfreeze all the parameters in transfer model, so it may take you some time to train this two models.
My models are all with high accuray, that is Basic CNN: 93.35%(15 epochs) ), Improved CNN: 93.85%(15 epochs) 94.38%(50 epoches), ResNet50: 94.47%(15 epochs), MobileNetV2: 94.70%.
However, you should notice that I didn't use any hyper parameters in my models and I use Test set as Validation set. So get a validation set from training data if you want to use hyper parameters.
