# Detecting COVID-19 with Chest X-Ray

In this repo, I attempted to predict COVID-19 disease from radiology images. In the experiment, ResNet18 was used and trained on the real chest X-Ray images of COVID-19 patients. The trained model was evaluated on 400 actual test images and achieved a sensitivity rate of 98% with 95% overall accuracy. The model classifies Chest X-Ray images in one of four classes: Normal, Viral, Pneumonio and COVID-19. 


### Installation
```bash
$ git clone https://github.com/spacewalk01/detecting-covid19-with-chest-XRay
$ cd detecting-covid19-with-chest-XRay
$ pip install -r requirements.txt
```
### Results

![alt text](covid_prediction.png)

![alt text](auc.png)

### Dataset

The database of chest X-ray images for COVID-19 positive cases along with Normal and Viral Pneumonia images. This COVID-19 dataset contains 3616 COVID-19 positive cases along with 10,192 Normal, 6012 Lung Opacity (Non-COVID lung infection) and 1345 Viral Pneumonia images.
- Viral pneumonia is an infection of your lungs caused by a virus. The most common cause is the flu, but you can also get viral pneumonia from the common cold and other viruses.

COVID-19 Radiography Dataset can be downloaded from [Kaggle](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database). 
- Download and put it in the project folder.


