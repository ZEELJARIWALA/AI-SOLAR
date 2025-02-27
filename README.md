# AI-SOLAR
## AI-SOLAR: Solar Panel Detection using YOLO

### Selection Task for SRIP Internship (Project by Nipun Batra)
I have successfully completed the selection task for the SRIP Internship Program and look forward to contributing to this project with dedication and innovation.

### Project Overview
Dataset: [Google Drive - Images (31 cm native resolution, 416x416 size)](https://drive.google.com/drive/folders/13QfMQ-7OdWKw-LR8DmypKwSHtI0Hk2wh?usp=sharing)

Labels and README: [Google Drive - Labels and README](https://drive.google.com/drive/folders/13QfMQ-7OdWKw-LR8DmypKwSHtI0Hk2wh?usp=sharing)

Label Description: [Figshare - Solar Panel Object Labels](https://figshare.com/articles/dataset/Solar_Panel_Object_Labels/22081091)

This project focuses on detecting solar panels using the YOLO object detection model. The dataset contains aerial images annotated in MS-COCO format with Horizontal Bounding Boxes (HBB). The key tasks involve data exploration, model training, evaluation, and metric computation to ensure robust performance.
This project focuses on detecting solar panels using the YOLO object detection model. The dataset contains aerial images annotated in MS-COCO format with Horizontal Bounding Boxes (HBB). The key tasks involve data exploration, model training, evaluation, and metric computation to ensure robust performance.

### Technologies & Libraries Used
- **Deep Learning & Object Detection:** Ultralytics YOLO, Torch
- **Data Processing & Analysis:** Pandas, NumPy
- **Geometric Computations:** Shapely
- **Visualization:** Matplotlib
- **Performance Evaluation:** Supervision, Scikit-learn
- **Others:** OS, Shutil, Glob, Google Colab

### Workflow
1. Project Setup
2. Importing Libraries
3. Data Exploration and Understanding
4. Dataset Statistics
5. Calculating Area of Solar Panels
6. Implementing Fundamental Functions
   - Intersection over Union (IoU)
   - Average Precision (AP)
   - Comparing AP50s on randomly generated data
7. Model Building and Evaluation
   - Splitting the Data (80-20 Train-Test Split, 10% Validation)
   - Training YOLO Model
   - Defining Helper Functions for Evaluation
   - Running Evaluation on Test Data
8. Interpretation and Insights

### Results & Metrics
- Computed IoU (Intersection over Union) using the Shapely library.
- Implemented Average Precision (AP) using Pascal VOC 11-point, COCO 101-point, and Area Under Precision-Recall Curve methods.
- Compared AP50 computed using three different methods.
- Trained and evaluated YOLO on the dataset, ensuring validation loss convergence.
- Computed mAP50 using supervision metrics and compared it with custom implementation.
- Generated a Precision, Recall, and F1-score table across different IoU and confidence thresholds.

### Visualizations
- Predicted solar panels using YOLO
- Displayed ground truth vs predicted bounding boxes on test images
- Plotted histograms of solar panel areas

### Conclusion
This project successfully demonstrates a structured approach to solar panel detection using YOLO, custom evaluation metrics, and comprehensive model performance analysis. I am eager to apply my knowledge and skills to the SRIP program and contribute meaningfully to its research initiatives.

### Acknowledgment
Special thanks to Nipun Batra for this opportunity and guidance.

