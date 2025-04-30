# Object_detection
OpenCV contains methods that can accept object detection weight/config files for a range of different object detection models. OpenCV can output confidence threshold and bounding box coordinates. This is extremely useful as OpenCV has methods that can accept bounding box coordinates to quickly plot boxes around the detected objects and label detected objects with a minimum amount of simple, clean code. OpenCV also has a method to apply Non-maximum Suppression (NMS), a technique used to prevent multiple detections of the same object by only keeping the detection with the highest confidence for that particular object.
![image alt](https://github.com/sanskritig741/Object_detection/blob/a52e02106498b24934cc62b44bee488bd2bf626c/output.png)


How to set up and run project.

1. Clone the Repository on Another Device

On the new device, open a terminal and run:

git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name


---

2. Set Up a Virtual Environment (Optional but Recommended):

python -m venv venv
source venv/bin/activate       
# On Windows: venv\Scripts\activate


---

3. Install Dependencies:

Make sure you have Python and pip installed. Then install the dependencies:

pip install -r requirements.txt

If you don’t have a requirements.txt, manually install:

pip install opencv-python numpy

(Include other libraries , like opencv , matplotlib, imutils.)


---

4. Run the Project:

Use the command:  object_detection.ipynb

---


5. Extra Notes:

project uses a webcam, make sure the  device has webcam .

If you're using pretrained models like YOLO or SSD, ensure they are included or downloaded at runtime.


dependencies or configurations are attached above 
1.frozen_inference_graph.p
2.labels.txt
3.ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt

![download](https://github.com/user-attachments/assets/1454f05d-2d95-48d6-8865-a64f76acfd46)

