
person counting - v1 2024-06-28 7:00am
==============================

This dataset was exported via roboflow.com on June 29, 2024 at 1:43 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 983 images.
Person are annotated in YOLOv8 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)
* Grayscale (CRT phosphor)

The following augmentation was applied to create 3 versions of each source image:
* Random exposure adjustment of between -13 and +13 percent
* Random Gaussian blur of between 0 and 1.1 pixels
* Salt and pepper noise was applied to 1.17 percent of pixels


