Welding Torch Annotation with YOLOv8
Overview
This project utilizes the YOLOv8 architecture to accurately detect and annotate welding torches in various industrial settings. The model can be used in quality control processes, automated inspection, and real-time monitoring systems in manufacturing.

Dataset
The dataset used for training the model consists of images of welding torches in different environments and angles. The images were annotated using bounding boxes to specify the location of the welding torch.

Model
The model is based on the YOLOv8 architecture, known for its speed and accuracy in object detection tasks. YOLOv8 improves on previous versions by incorporating:

Improved anchor-free detection head.
Advanced data augmentation techniques.
Efficient training and inference processes.

Training
The model was trained using the following configuration:

Framework: Ultralytics YOLOv8
Hardware: GPU (Specify if using a specific GPU, e.g., NVIDIA RTX 3080)
Learning Rate: 0.001 (adjusted with a learning rate scheduler)
Optimizer: AdamW

Training Command
yolo train data=./data.yaml model=yolov8n.pt epochs=100 imgsz=640

Contributing
Contributions are welcome! Please follow the contributing guidelines to submit issues or pull requests.

License
This project is licensed under the MIT License - see the LICENSE file for details.