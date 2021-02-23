# Breast-Cancer-Histopathology-Detection

Invasive ductal carcinoma (IDC) is the most common subtype of all breast cancers. To assign an aggressiveness rating to an entire montage sample, pathologists typically focus on regions that contain IDC. Accordingly, one of the common preprocessing steps for automatic classification of aggressiveness is to delineate the exact regions of IDC within an entire mounting slide. That's why we thought to detect the regions that are affected.
   
So for treatment, we tried to use the CNN model for X-ray images that contain IDC to find out which patients are likely to have breast cancer. We could carry out the processing on the images with the Keras library as well as Transfer Learning and we obtained a model which an accuracy which exceeds 80% and the detection of the images with a positive IDC and a negative IDC.
