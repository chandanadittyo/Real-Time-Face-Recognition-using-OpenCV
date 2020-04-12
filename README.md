# Real-Time-Face-Recognition-using-OpenCV
Real Time Face Recognition Using OpenCV
<!DOCTYPE html>
<html>
<head>
	<title>Real-Time-Face-Recognition-using-OpenCV</title>
</head>
<body>
	<h2>/<h2>
	<h3>Package Needed</h3>
	<li>OpenCV</li>
	<li>Numpy</li>
	<li>Pillow</li>
	<h3>Instruction</h3>
	<li>Download this repository as zip file and unzip it to a folder.</li>
	<li>Create two folders named "dataSet' & 'trainer'</li>
	<li>Run 'face_dataset.py' and enter id 1 for first person then system will take your pictures for training and save it in 'dataSet' folder</li>
	<li>Run 'face_training.py', it will train the model and save in 'trainer'</li>
	<li>Open 'face_recognition.py' and write your trained names sequentially according to the id at line 19</li>
	<li>Run 'face_recognition.py' </li>
	<h3>*****Special Note*****</h3>
	<li>If any one face this problem "AttributeError: module 'cv2.cv2' has no attribute 'face'" Then Open your Python Command Shell and type 
	"pip install opencv-contrib-python --upgrade"</li>


</body>
</html>
