# CNN for detect melanoma.
> building a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma.


## Table of Contents
* [General Info](#general-information) creation of model for accurate detection of melanoma cancer
* [Technologies Used](#technologies-used) CNN model has been implemented for detection of melanoma cancer using data set of various skin disease
* [Conclusions](#conclusions)A CNN model can accurately predict/detect melanoma cancer by training the model with given set of data.

## General Information
- Model is created & trained on given set of data for accurate detection of melanoma by analysing image of skin disease.
- What is the background of your project? Data set contain of 9 classes of disease and a model is trained on given dataset using CNN technology  
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used? Data set contains of images of skin disease of 9 classes. 


## Conclusions
- Conclusion 1 from the analysis is that CNN basic model has trained well on training data with good accuracy but initial model does not perform well on validation data and therefore model parameters tweak is required.
- Conclusion 2 After tweaking of CNN layer parameters value in model no significant improvement has been seen in validation accuracy.   
- Conclusion 3 After trying to drop layer from CNN model no significant improvement has been seen in validation accuracy.
- Conclusion 4 After using augumention and distribution of training data images to all the classes validation accuracy has increased significantl.


## Technologies Used
- Major library used -
pathlib
tensorflow 
matplotlib.pyplot
numpy 
pandas
os
PIL
zipfile
Augumentation


## Acknowledgements
- This project on CNN model was inspired by UPGRAD team


## Contact
Created by [@] - feel free to contact me!

