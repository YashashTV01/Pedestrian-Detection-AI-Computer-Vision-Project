# **Pedestrian Detection using OpenCV & Haar Cascade**  

## **📌 Overview**  
This project implements a **real-time pedestrian detection model** using **OpenCV and Haar Cascade classifiers**. Pedestrian detection is an essential component in **intelligent video surveillance systems**, traffic monitoring, and autonomous vehicles, as it enables accurate detection of people in a given frame or live video feed.  

## **🔍 Problem Statement**  
The objective is to build an **efficient pedestrian detection model** using Python and OpenCV, leveraging the **Haar Cascade classifier** for detecting pedestrians in images and videos.  

## **📂 Dataset**  
- The project primarily uses **pre-trained Haar Cascade XML files** for pedestrian detection.  
- Sample test images and videos are included in the repository.  

## **🛠️ Technologies Used**  
- **Python**  
- **OpenCV** (Computer Vision Library)  
- **Haar Cascade Classifier** (Pre-trained model for object detection)  
- **NumPy** (For data handling)  

## **🚀 Features**  
✅ **Real-time pedestrian detection** using OpenCV.  
✅ **Works with both images and video feeds** (webcam & pre-recorded videos).  
✅ **Optimized Haar Cascade model** for efficient detection.  
✅ **Frame-by-frame pedestrian tracking** with bounding boxes.  
✅ **Customizable parameters** for fine-tuning detection accuracy.  

## **📥 Installation**  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/YashashTV01/Pedestrian-Detection.git
   cd Pedestrian-Detection
   ```  

2. **Install dependencies**  
   ```bash
   pip install opencv-python numpy
   ```  

## **🖥️ Usage**  

### **🔹 Detect Pedestrians in an Image**  
Run the following command to detect pedestrians in a static image:  
```bash
python pedestrian_detector.py --image test_image.jpg
```  

### **🔹 Detect Pedestrians in a Video**  
Run the following command to detect pedestrians in a video file:  
```bash
python pedestrian_detector.py --video test_video.mp4
```  

### **🔹 Real-Time Detection (Webcam)**  
To use the webcam for real-time pedestrian detection, run:  
```bash
python pedestrian_detector.py --webcam
```  

## **📊 Results & Performance**  
- The **Haar Cascade Classifier** provides efficient and fast pedestrian detection.  
- Optimized the model by **tuning scale factors and minimum neighbors** for better accuracy.  
- The detection model works well in **daylight conditions** but may require fine-tuning for **low-light environments**.  

## **📌 Future Improvements**  
🔹 Implement **Deep Learning-based models** (e.g., YOLO, SSD) for improved accuracy.  
🔹 Integrate **object tracking algorithms** for better pedestrian movement tracking.  
🔹 Optimize performance for real-time processing in **edge devices**.  

## **📜 License**  
This project is licensed under the **MIT License** – feel free to use and modify it!  

## **🤝 Contributing**  
Contributions are welcome! If you have suggestions or improvements, feel free to **fork** this repo and submit a **pull request**.  
