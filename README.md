# Diabetic-Retinopathy
[Video Description Here](https://www.youtube.com/watch?v=mDEfWfvOvLQ) (Note, this is for an older version of the model but is still applicable! Sorry for the poor quality, screen capture wasn't working.)

# Diabetic-Retinopathy Classifier (25 epochs, 62% validation, and likely to improve with more extensive pre-processing)
Take in public data of human eye scans, and determine severity of diabetic retinopathy, which is likely to result in other medical problems related to the eye and possible blindness.
## Team members
Sean Flannery (SeanFlannery)
## Goals
- Achieve high accuracy classifying diabetic retinopathy risk
- Beat top 10% of state-of-the-art classifiers using new neural network methods
## Challenges
- Acquisition of data (https://github.com/beamandrew/medical-data)
  - Overcome thanks to Indian Diabetic Retinopathy Image Dataset (IDRiD)
- Cropping user images appropriately so that they interface with NN properly (often the images are surrounded with black)
## Acknowledgements
- There was a fantastic kaggle competition based on the IDRiD, but I have chosen to do the image processing from scratch to gain a better understanding of relevant libraries
## Restrictions --optional--
"I want to eat ice-cream if I pass." -- Not if you care about your eyes!

## Results
- Validation accuracy of 62% reaches top 10% of kaggle submissions on Diabetic-Retinopathy [Kaggle Competition](https://www.kaggle.com/c/diabetic-retinopathy-detection/leaderboard)
- Better than expected loss rates for ResNet50 transfer learning
- Likely would have improved beyond 62% test accuracy on 5-class classification
- Noticed that due to the generation of random perturbations in the training data accuracy for training did not exceed testing epochs for quite a long time

## Conclusions
- Nothing beats more data, but doing random perturbations and disturbances can make a model generalize better
- On relatively small dataset, determine if augmenting the data could work to improve validation accuracy!

## ToDo
- Augment data in different fashions (increase rotation degree, average by pixel)
- Attempt to crop by black background to clean data
- Acquire more data! 
- Acquire more GPUs
