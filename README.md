# Diabetic-Retinopathy
[Video Description Here](https://www.youtube.com/watch?v=mDEfWfvOvLQ)

# Diabetic-Retinopathy Classifier (25 epochs, 55% validation, and likely to improve with time)
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
- Better than expected loss rates for ResNet50 transfer learning
- Likely would have improved beyond 55% test accuracy on 5-class classification
- All data sources, weights, and statistics may be found [here](https://drive.google.com/drive/folders/1qQuFN3QiyeFe-1V0zTeM_eJfRYRspEiB?usp=sharing) in the event that you'd like to expand on the training!

## ToDo
- Augment data more
- Acquire more data
- Acquire more GPUs
