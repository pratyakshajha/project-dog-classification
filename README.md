## Project Overview

This repository hosts code used in second project on Convolutional Neural Networks (CNN) project in the Deep Learning Nanodegree. In addition to meeting the project specifications, I also added on a few things. 

Given an image of a dog, the algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, it will identify the resembling dog breed.  

## Project To Do List

### Rubrics
| Criteria                                           | Specifications                                                                                                                                                                                        | Finished |
|----------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
| Assess the Human Face Detector                     | The submission returns the percentage of the first 100 images in the dog and human face datasets that include a detected, human face.                                                 |<ul><li>[x] </li></ul>|
| Implement a Dog Detector                           | Use a pre-trained VGG16 Net to find the predicted class for a given image. Use this to complete a  dog_detector function below that returns True if a dog is detected in an image (and False if not). |<ul><li>[x] </li></ul>|
| Assess the Dog Detector                            | The submission returns the percentage of the first 100 images in the dog and human face datasets that include a detected dog.                                                                |<ul><li>[x] </li></ul>|
| Create a CNN to Classify Dog Breeds (from Scratch) | Specify model architecture, train and test model   |<ul><li>[x] </li></ul>|
| Create a CNN Using Transfer Learning               | Specify model architecture, train and test model  |<ul><li>[x] </li></ul>|
| Prepare report                        | Refer the [rubrics](https://review.udacity.com/#!/rubrics/2259/view)  |<ul><li>[x] </li></ul>|


### Additional
- [ ] Webapp using flask
- [ ] Overlay a Snapchat-like filter with dog ears on detected human heads.
- [ ] Added functionality: A single class with highest probability is shown. Added topk classes, if probability is less than a threshold.
- [ ] Experiment with multiple dog and human detectors.
