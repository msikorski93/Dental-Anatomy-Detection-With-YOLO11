# Dental-Anatomy-Detection-With-YOLO11
![ alt text ](https://img.shields.io/badge/license-MIT-green?style=&logo=)
![ alt text ](https://img.shields.io/badge/-Jupyter-F37626?logo=Jupyter&logoColor=white)
![ alt text ](https://img.shields.io/badge/-YOLO-111F68?logo=YOLO&logoColor=white)
![ alt text ](https://img.shields.io/badge/-Weights_&_Biases-FFBE00?logo=weightsandbiases&logoColor=black)
![ alt text ](https://img.shields.io/badge/-Ultralytics-111F68?logo=Ultralytics&logoColor=white)
![ alt text ](https://img.shields.io/badge/-OpenCV-5C3EE8?logo=OpenCV&logoColor=white)
![ alt text ](https://img.shields.io/badge/-NumPy-013243?logo=Numpy&logoColor=white)
![ alt text ](https://img.shields.io/badge/-Roboflow-6706CE?logo=Roboflow&logoColor=white)

This project investigated the YOLO11n nano network, emphasizing its application for dental anatomy detection. The dataset originates from Roboflow. This type of transfer learning, implementing a pre-defined model on a new dataset, proved to be very useful and accurate. The model demonstrated strong performance with high accuracy in detecting tooth anatomy across a variety of images. The network effectively identified different tooth classes and localized them with high precision. 30 training epochs were enough for accurate results.

A few examples were performed and for each run we achieved the following evaluation scores:

| **Example** | **Precision** | **Recall** | **F1 Score** | **mAP@50** | **mAP@50:95** | **Weighted<br>Fitness** | **Unweighted<br>Fitness** |
|-------------|---------------|------------|--------------|------------|---------------|-------------------------|---------------------------|
|    **1**    | 1.0000        | 0.9231     | 0.9600       | 1.0000     | 0.8417        | 0.9457                  | 0.9412                    |
|    **2**    | 0.9600        | 1.0000     | 0.9796       | 0.9600     | 0.7800        | 0.9329                  | 0.9250                    |
|    **3**    | 1.0000        | 1.0000     | 1.0000       | 1.0000     | 0.8286        | 0.9629                  | 0.9571                    |
|    **4**    | 0.9600        | 1.0000     | 0.9796       | 0.9600     | 0.7400        | 0.9264                  | 0.9150                    |
|    **5**    | 1.0000        | 1.0000     | 1.0000       | 1.0000     | 0.8417        | 0.9653                  | 0.9604                    |

Dental images with background overlays, including bounding boxes and confidence scores for each tooth type:
<img src='https://github.com/user-attachments/assets/41a97f2f-7c9b-478b-bd35-66d81a9f4791' width='500'/>

<img src='https://github.com/user-attachments/assets/f9988848-1eeb-4144-b618-f426512f2b84' width='500'/>

Overall, YOLO11 proves to be a reliable and efficient tool for dental image analysis, with its speed and performance making it suitable for real-time applications.
