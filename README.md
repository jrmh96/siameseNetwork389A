Multi-Label Classification on kaggle dataset (5606 pictures): https://www.kaggle.com/nih-chest-xrays/sample

Sample label format: 

Image Index	          Finding Labels	                                   
00000013_005.png	Emphysema|Infiltration|Pleural_Thickening|Pneumothorax	

This dataset is a ***sample*** of the complete x-ray dataset, with the entire dataset containing 30000+ pictures. 

Categorical Accuracy of 53% on validation set

To run code: import the notebook file to google colab and run. Import picture dataset to a google drive folder and replace folder id with the corresponding folder id to import.

TODO:
Implement residual network layers: https://arxiv.org/abs/1512.03385
Train on the entire data set
