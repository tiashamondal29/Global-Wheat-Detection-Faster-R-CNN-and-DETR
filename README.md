# Global-Wheat-Detection-Faster-R-CNN-and-DETR


<h1>Overview/Summary</h1>
Wheat products are widely consumed and extensively studied, making wheat fields an important area of research. This project focuses on evaluating the performance of two popular object detection models, Faster R-CNN and DETR, on the Global Wheat Detection dataset. The dataset consists of images of wheat fields, and the objective is to detect individual wheat heads in these images. By comparing the performance of the models using various evaluation metrics, we aim to determine which model is better suited for this task.

<h1>Aim</h1>
The aim of this project is to evaluate the performance of Faster R-CNN and DETR models on the [Global Wheat Detection dataset](https://www.kaggle.com/competitions/global-wheat-detection/overview) and compare their results using relevant metrics. The report provides a comprehensive analysis of the models' accuracy, precision, recall, and mean average precision (mAP) on the dataset. This analysis helps in identifying the model that performs better in detecting wheat heads in the images. The [report](/Comparision_between_Faster-RCNN_and_DETR.ipynb) also highlights the strengths and weaknesses of each model and offers recommendations for future research in this area.

<h1>Main Findings</h1>
**Model Performance Metrics:** The evaluation of the models involved recording the mean average precision (mAP) at different intersection over union (IoU) thresholds and the recall value. The R-CNN model achieved a slightly higher mAP value than the DETR model, indicating better overall performance in detecting wheat heads. Moreover, the recall value for the R-CNN model was higher, suggesting its ability to identify more instances of wheat heads. Based on these metrics, the R-CNN model appears to be a better choice for wheat head detection on the Global Wheat Detection dataset, although both models demonstrate relatively low mAP and recall values. Further investigation into factors such as model architecture and training data may help improve performance.

**Training and Evaluation Methodology:** The training and evaluation process for the R-CNN and DETR models involved preprocessing the data, applying data augmentation techniques, defining suitable loss functions, and optimizing hyperparameters using a validation set. Cross-validation was performed to ensure the models neither overfit nor underfit the data.

*Please refer to the detailed report for a comprehensive analysis of the models' performance and the methodology employed in this project.*
