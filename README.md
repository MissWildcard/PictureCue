# PictureCue
Cakewalk: Image Captioning for Cake Images using Stable Diffusion Augmentation  

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
Run 1_DatasetGeneration.ipynb to extract the required cake images and captions<br />

