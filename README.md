# Skin-Lesion_Segmentation

Skin lesion segmentation is an important process in skin diagnostics because it improves manual and computer-aided diagnostics by focusing the medical personnel on specific parts of the skin. One of the most dangerous types of this cancer is melanoma which requires an early and accurate detection. However, automatic melanoma segmentation on dermoscopic images is a challenging task since images are corrupted by noise like hairs, air bubbles, blood vessel... and with fuzzy boundaries.

Image segmentation is a common task in computer vision that partitions a digital image into multiple segments, for which deep neural networks have been proven to be reliable. In this project,  a Deep Learning architecture called SegNet has been used. The model is trained on limited images from PH2 dataset which includes the manual segmentation, the clinical diagnosis, and the identiﬁcation of several dermoscopic structures, performed by expert dermatologists.

### RESULT

The proposed approach are applied on PH2 dataset. The three methods of image augmentation increases the number of images from 200 to 650 resulting into a total of 1300 images containing the rgb images and their true mask. The Segnet network took 13 seconds per step over 120 epochs resulting in the total duration of  26 minutes. The Jaccard Index obtained after 120 epochs on training set is 94.28% and on the validation set is 90.87%. The dice coefficient obtained after 120 epochs on training set is 86.55% and on validation set 82.35%. The  precision obtained after 120 epochs on training set is 89.60% and on validation set 84.03%. The recall obtained after 120 epochs on training set is 92.22% and on validation set 88.67%. The accuracy obtained after 120 epochs on training set is 94.17% and on validation set 90.56%. The threshold value used is chosen merely based on the experimental resuts and has no theoritical principle behind the exact value.

### Dataset used : PH2 Dataset

