# Detecting COVID-19 with Chest X-Ray

In this repo, I attempted to predict COVID-19 disease from radiology images. In the experiment, ResNet18 was used and trained on the real chest X-Ray images of COVID-19 patients. The model was evaluated on 400 test images and achieved a sensitivity rate of 98% with 95% overall accuracy. The model classifies Chest X-Ray images in one of four classes: Normal, Viral, Pneumonio and COVID-19. The database of chest X-ray images for COVID-19 positive cases along with Normal and Viral Pneumonia images. This COVID-19 dataset contains 3616 COVID-19 positive cases along with 10,192 Normal, 6012 Lung Opacity (Non-COVID lung infection) and 1345 Viral Pneumonia images.


# Installation

$ git clone https://github.com/spacewalk01/detecting-covid19-with-chest-XRay
$ cd detecting-covid19-with-chest-XRay
$ pip install -r requirements.txt

## Results

![alt text](covid_prediction.png)

## Dataset

Dataset from COVID-19 Radiography can be downloaded from Kaggle. 
- Download it and put it in the project folder.

- Viral pneumonia is an infection of your lungs caused by a virus. The most common cause is the flu, but you can also get viral pneumonia from the common cold and other viruses.
