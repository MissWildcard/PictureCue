# PictureCue
Cakewalk: Image Captioning for Cake Images using Stable Diffusion Augmentation

**Step0:**
Before running the notebook, make sure that you have downloaded the COCO dataset

Foe donwloading the dataset, you may use :

wget http://images.cocodataset.org/zips/train2017.zip 
wget http://images.cocodataset.org/zips/val2017.zip 
wget http://images.cocodataset.org/zips/test2017.zip 
wget http://images.cocodataset.org/zips/unlabeled2017.zip

Go to the respective directory and unzip them using:

unzip train2017.zip 
unzip val2017.zip 
unzip test2017.zip 
unzip unlabeled2017.zip

rm train2017.zip 
rm val2017.zip 
rm test2017.zip 
rm unlabeled2017.zip

**Step1:**
Run 1_DatasetGeneration.ipynb to extract the required cake images and captions

