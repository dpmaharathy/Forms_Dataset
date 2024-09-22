## This repository contains the files to preprocess the forms dataset from https://github.com/forms-data-structures/forms-data.


## The ECCV_data folder contains 300 images and WACV_data folder contains 100 images along with their json annotations.

# ECCV preprocessing
## preprocessing_eccv.ipynb file contains the code to preprocess the eccv folder images.
## We load the images and json files and plot the checkboxes around the images and store them on a new directory img_bbox and img_bbox_wid.
## The img_bbox folder contains images with bounding boxes around both choicefields and widgets and img_bbox_wid contains only bounding box around the images.
## We observed that there were some errors on the json annotations and the widgets were not properly annotated. So we only plotted the bounding box around the widgets for which the absolute width and height difference is less than or equal to 15 pixels.

## The yolo annotations of these images are also stores on the yolo_annotations directory with the same name in .txt files

# WACV preprocessing
## preprocessing_wacv.ipynb file contains the code to preprocess the wacv folder images.
## We load the images and json files and plot the checkboxes around the images and store them on a new directory img_bbox and img_bbox_wid.
## The img_bbox folder contains images with bounding boxes around both choicefields and widgets and img_bbox_wid contains only bounding box around the images.

## The yolo annotations of these images are also stores on the yolo_annotations directory with the same name in .txt files

