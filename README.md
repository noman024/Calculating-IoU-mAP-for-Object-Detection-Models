# Calculating-IoU-mAP-for-Object-Detection-Models

This Python script calculates the mAP of any object detection model. It takes 5 ground-truth boxes and 5 predicted boxes and computes the Intersection over Union (IoU), confusion matrix (TP, FP), Average Precision (AP), and Mean Average Precision (mAP), finally plotting the Precision-Recall curve.

## **Requirements**
- numpy

## **Steps**
To use this script, follow the steps below:

- Create ground truth boxes manually in the following manner: [x, y, width, height, class-label].
- Create predicted boxes manually in the following manner: [x, y, width, height, confidence score].
- Sort predicted boxes in descending order based on confidence score.
- Compute the Intersection over Union (IoU) to check the overlapping between a predicted box and any ground-truth box.
- Compute the confusion matrix for calculating Average Precision (true positive, false positive).
- Compute the Average Precision for calculating the mAP.
- Compute the Mean Average Precision (mAP).
- Visualize some plots for better understanding.

## **Troubleshooting**
If you encounter any issues while running this script, feel free to raise an issue in the GitHub repository.
