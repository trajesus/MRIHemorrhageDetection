## Macrohemorrhage segmentation in MRI scans

The segmentation and assessment of intracranial hemorrhages are very complex and a continuous challenge for physicians.
As a means to improve and automize brain hemorrhage segmentation, deep learning has the potential to address this problem through the use of artificial neural networks.
A two-stage approach was employed, in the first stage, the classification process took part in identifying scans with macrohemorrhages through a DenseNet, in the second stage, the macrohemorrhage segmentation took place through an AttentionUnet network. With the resulting network an average dice score of 0.77 and a dice loss of 0.23 were obtained.
For this project, a dataset containing MRI scans of 65 patients with intracranial hemorrhages was used to train and evaluate the model. 

In this project there are 3 main files: As mentioned the classification process can be found in the ClassificationModel.ipynb file, the segmentation process can be found in the SegmentationModel.ipynb file, while the most important file is FinalSegmentationModel.ipynb which makes use of the both previous models to conclude the final automatic macrohemorrhage segmentation model.

Both the remaining Results_classification and Results_segmentation files refer to the best models saved during the development process.