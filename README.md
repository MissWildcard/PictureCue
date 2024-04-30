# PictureCue
###Cakewalk: Image Captioning for Cake Images using Stable Diffusion Augmentation  

**Step0:**<br />
Before running the notebook, make sure that you have downloaded the COCO dataset <br />

Foe donwloading the dataset, you may use :<br />

wget http://images.cocodataset.org/zips/train2017.zip  <br />
wget http://images.cocodataset.org/zips/val2017.zip <br />
wget http://images.cocodataset.org/zips/test2017.zip <br />
wget http://images.cocodataset.org/zips/unlabeled2017.zip<br />

Go to the respective directory and unzip them using:<br />
<br />
unzip train2017.zip <br />
unzip val2017.zip <br />
unzip test2017.zip <br />
unzip unlabeled2017.zip <br />

rm train2017.zip <br />
rm val2017.zip <br />
rm test2017.zip <br />
rm unlabeled2017.zip <br />

**Step1:** <br />
Run 1_DatasetGeneration.ipynb to extract the required cake images (2.9k dataset) and captions<br />

**Step2:** <br />
Run 2_DatasetAugmentation_withSD.ipynb to generate synthetic cake images using stable diffuion<br />
Merge the synthetic images and original images into a single folder (5.9k dataset)  <br />
At this point you may run Similaritymatrix.ipyng to have an understanding about the images and its captions <br />

**Step3:** <br />
Run 3_ModelTraining.ipynb to train your model on both the original dataset and the synthetic dataset<br />
It is recommended to give appropriate name while saving these model to your directory <br />

**Step4:** <br />
Load saved model and run 4_ModelEvaluation.ipynb to evaluate the model using BLEU scores <br />

You may use either of our models (one trained on original 2.9k dataset and the other on 5.9k augmented dataset) for inference <br />
You may use the cake sample images from Data/cake_samples.zip. <br />
You can also use your own cake images on our model <br />
Run DEMO.ipynb for this <br />




