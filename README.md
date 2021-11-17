# Marine_trash_object_detection-CAPSTONE-
Problem:
Every year, over 8 millions tons of trash end up in the ocean. This has negative implications for sea life, human health, and economies, to mention a few.
Proposed solution:
A cleaning robot capable of detecting and removing trash. This project is an attempt at creating an object detection model capable of detecting trash in the ocean for that purpose.
I used Detectron2. A pre-trained Faster R CNN baseline model was trained on the dataset.
The dataset, DeepTrash DataSet, used contained 1900 training images, 637 test images, 637 validation images (60, 20, 20 split)
The labelled (bounding boxes) images were sourced from:
1. Field images from video frames filmed on a GoPro from Lake Tahoe, San Francisco Bay and Bodega Bay in CA.
2. Internet images (<20%) taken by scraping Google Images.
3. Deep Sea images are from JAMSTEK JEDI dataset: http://www.godac.jamstec.go.jp/
dataset author: https://github.com/gautamtata/DeepPlastic
