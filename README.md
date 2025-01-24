# TumorSegmentation
This repository provide you codes of DAM-UNET, UNET, VNET, SegNet, SegResNet, MaskRCNN for the Medical Segmentation Decathlon (MSD) of Lung Tumorous.

Step#1: Download the complete repository.

Step#2: Intstall the dependencies like PyTorch, torchvision, seaborn etc 

Step#3: Download the MSD LungTumerous dataset (i.e., Task06_Lung.tar) https://drive.google.com/drive/folders/1HqEgzS8BV2c7xYNrZdEAnrHk7osJJ--2 and extract the downloaded dataset. Place code and dataset on the same folder.

Step#4: Preprocess the dataset using Preprocessing.py and Preprocess-CT/Masks.py files. Here you need to adjust the slices and mask path in both files.

Step#5: Start training and validation. For example, train SegNet.py using prompt command i.e., python SegNet.py. 

Step#6: Check out the results.

Step#7: Repeat Step#5 and Step#6 to train and visualize results for other models.
