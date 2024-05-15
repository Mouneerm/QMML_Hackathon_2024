In this Hackathon, we trained an improved version of the ResNet-18 on the Imagewoof, a challenging subset of 10 classes from Imagenet, all of which are dog breeds. 
The breeds included Australian terrier, Border terrier, Samoyed, Beagle, Shih-Tzu, English foxhound, Rhodesian ridgeback, Dingo, Golden retriever, and Old English sheepdog.

Our model msut adhere to the Residual Network architecture, as detailed in the provided paper: https://arxiv.org/pdf/1512.03385.pdf

 We were modified the original network by adding and removing some layers and implemented soft-label cross entropy, warmup and cosine annealing learning rate, data augemntation and much more.

Improvements were inpired by the paper [Bag of Tricks for Image Classification with Convolutional Neural Networks](https://arxiv.org/abs/1812.01187)

As per the competition rules, there were bounties and penalties in play. Bounties offered a score multiplier, which would be applied to our final accuracy score for our model submission.

For more info about the competition: https://www.kaggle.com/competitions/the-queen-mary-machine-learning-hackathon-february

And as a souvenir of our team work: 

![image](https://github.com/Mouneerm/QMML_Hackathon_2024/assets/45911394/9f3774c2-dcca-4d4a-bba3-93ed44836251)
