# Using transfer learning for face recognition

Generally the most hactic process in the process of developing a model for a convoluitonal neural network is getting a dataset big enough to train the model with good accuracy and prevening overfitting and underfitting. The other main problem is the huge time and resources(cu,ram,etc.) requirement. Tranfer learning and fine tuning is a solution to both the above problems. It involves using a pre built network like VGG, ResNet, or MobileNet with a set of pretrained weights on some particular dataset like imagenet and adding some addiitonal layers to it for the detection of the object required by you. Training these types of making by ffreezing the prebuilt layers and training only the newly added layers will not only train the model faster but will also provide a lot better accuracy and require a lot les resources.
