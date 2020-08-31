# Galaxy Morphology Classification using EfficientNets

## Abstract

We study the usage of EfficientNets and their applications to Galaxy Morphology Classification. We explore the usage of EfficientNets into predicting the 
vote fractions of the 79,975 testing images from the Galaxy Zoo 2 challenge on Kaggle. We evaluate this model using the standard competition metric i.e. rmse score 
and rank among the top 3 on the public leaderboard with a public score of 0.07765. We propose a fine-tuned architecture using EfficientNetB5 to classify galaxies into
seven classes - completely round smooth, in-between smooth, cigar-shaped smooth, lenticular, barred spiral, unbarred spiral and irregular. The network along 
with other popular convolutional networks are used to classify 29,941 galaxy images. Different metrics such as accuracy, recall, precision, F1 score are used 
to evaluate the performance of the model along with a comparative study of other state of the art convolutional models to determine which one performs the best. 
We obtain an accuracy of 93.7\% on our classification model with an F1 score of 0.8857. EfficientNets can be applied to large scale galaxy classification in future 
optical space surveys which will provide a large amount of data such as the Large Synoptic Space Telescope.
