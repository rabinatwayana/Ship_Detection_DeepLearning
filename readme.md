## Deep Learning–Based Ship Detection in SAR Imagery

#### Background


#### Objectives

The main objective of this project is to develop and evaluate deep learning–based methods for ship detection in Synthetic Aperture Radar (SAR) imagery. 
The specific objectives are:

- To implement and train deep learning models, including YOLO, DETR, and Faster R-CNN, for detecting ships in SAR data.

- To compare the performance of these models in terms of accuracy, F1-score, and computational efficiency.

#### Datasets

For the experiment, data were accessed from kaggle [SARscope](https://www.kaggle.com/datasets/kailaspsudheer/sarscope-unveiling-the-maritime-landscape). It contains a total of 6,735 SAR images, supporting both detection and segmentation tasks.

The Key features of datasets are as follow:

- Dual-purpose dataset: Suitable for ship detection and instance segmentation

- High-resolution data: 5,719 SAR images resized to 640 × 640, with 17,708 ship instances

- Polarizations: Includes VV and VH channels

- Efficient processing: Images resized for faster training and stored using lossless compression

- Balanced split: 70% training, 20% validation, 10% testing

= Standard format: Annotations provided in COCO (MMDetection-compatible) format

#### Models

#### Results and Discussions
