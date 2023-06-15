<h1>Object-Detection</h1>
This repository contains an object detection model implemented in Python using OpenCV and MobileNet-SSD V3. The model is trained to detect various objects in images and video clips and provides bounding box coordinates along with class labels for the detected objects. The MobileNet-SSD V3 model is based on the work by the OpenCV team. Please refer to the <a href="https://github.com/opencv/opencv/wiki/TensorFlow-Object-Detection-API#pre-trained-models" target="_blank">OpenCV documentation</a> for more information.<br>
<img width="572" alt="objd" src="https://github.com/Indranath165/Object-Detection/assets/121590717/438669bf-f9d0-48ef-99b5-100b3c92be9c">

<h2>Features</h2>
<ul>
    <li>Object detection in images</li>
    <li>Object detection in video clips</li>
    <li>Adjustable confidence threshold for object detection</li>
    <li>Customizable pre-trained model support</li>
</ul>
<h2>Installation</h2>
<ol>
    <li>Clone or download this repository to your local machine.</li>
    <li>Install the required dependencies: <code>pip install -r requirements.txt</code> </li>
    <li>Make sure you have Python 3.6 or above installed.</li>
</ol>
<h2>Usage</h2>
<h3>Object Detection on Images</h3>
<ol>
    <li>Run the provided Jupyter Notebook file <b>Object Detection.ipynb</b></li>
    <li>In the notebook, locate the following line of code:<br> <code>img = cv2.imread('car.jpg')</code><br>Replace 'car.jpg' with the path and filename of your desired image. Make sure the image is placed in the same directory as the Jupyter Notebook file.</li>
    <li>Execute the code cell to perform object detection on the image.</li>
    <li>The notebook will output the detected objects along with their bounding box coordinates and confidence scores. The annotated image will be displayed in the notebook.</li>
</ol>
<h3>Object Detection on Video Clips</h3>
<ol>
    <li>Run the provided Jupyter Notebook file <b>Object Detection.ipynb</b></li>
    <li>In the notebook, locate the following line of code: <br> <code>cap = cv2.VideoCapture("sample1.mp4")</code><br>Replace "sample1.mp4" with the path and filename of your desired video clip. Make sure the video clip is placed in the same directory as the Jupyter Notebook file.</li>
    <li>Execute the code cells to perform object detection on the video clip.</li>
    <li>The notebook will process the video clip frame by frame, detect objects in each frame, and display the annotated video in the notebook.</li>
</ol>
<h2>Technologies Used</h2>
<ul>
    <li>Python</li>
    <li>OpenCV</li>
    <li>MobileNet-SSD V3</li>
</ul>
<h2>Contributions</h2>
Contributions are welcome! We value your input and encourage you to actively participate in the project. If you have any ideas, suggestions, bug reports, or feature requests, please don't hesitate to open an issue on GitHub. Additionally, we appreciate any code contributions you may have. If you'd like to contribute code, please submit a pull request, and we will review it as soon as possible. Thank you for your support!
