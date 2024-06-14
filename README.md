# Weapon Detection with YOLOv8 for Security Cameras

This repository demonstrates the use of YOLOv8 for detecting weapons in security camera footage. The workflow includes:

1. **Installation and Setup**: Installation of necessary packages including `ultralytics` for YOLOv8.

2. **Object Detection**: Utilizing YOLOv8 for object detection on both videos and photos.

3. **Segmentation and Classification**: Additional tasks performed beyond basic object detection.

4. **Fine-Tuning**: Due to limitations in detecting weapons like pistols and knives with the pretrained model, we fine-tuned YOLOv8 on a custom dataset.

5. **Evaluation**: Testing the `best.pt` model on a separate test dataset, generating confusion matrices and other evaluation metrics.

6. **Validation Results**: Displaying successful object detection instances from the validation dataset.

This repository aims to enhance security camera capabilities by improving weapon detection accuracy using YOLOv8.


