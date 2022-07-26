# Mask-Detection-using-machine-learning
* A Mask Detection program which uses OpenCV and Haar Cascade.
* We can perform mask detection on images, videos and live.

<div>
<p float="center">
  <img src="Mask-Detection-using-machine-learning/working screenshots/main.jpg" alt="Main page" width="400" />
</p>
</div>

* For the calculation and representation it uses OpenCV.
* For the GUI of the program it uses Tkinter.
* To detect face, nose and mouth in a frame it uses Haar Cascade.
* Based on the features identified in a frame it concludes if the person is wearing Half Mask, Full Mask or NO Mask. The features selected for this are nose and mouth.

<div>
<h1> Data Source: Image
 <hr>
  <p float="left">
    <img src="Mask-Detection-using-machine-learning/working screenshots/mask.jpg" alt="Mask" width="450" />
    <img src="Mask-Detection-using-machine-learning/working screenshots/half mask 1.jpg" alt="half Mask" width="450" />
    <img src="Mask-Detection-using-machine-learning/working screenshots/nomask 1.jpg" alt="no Mask" width="450" />
    <img src="Mask-Detection-using-machine-learning/working screenshots/no mask 2.jpg" alt="no Mask" width="450" />
  </p>

  
  <h1> Data Source: Live Video Streaming
  <hr>
    <p float="left">
      <img src="Mask-Detection-using-machine-learning/working screenshots/live mask.jpg" alt="Mask" width="450" />
      <img src="Mask-Detection-using-machine-learning/working screenshots/live half mask.jpg" alt="half Mask" width="450" />
      <img src="Mask-Detection-using-machine-learning/working screenshots/live no mask.jpg" alt="no Mask" width="450" />
    </p>
</div>

* With the help of the control panel we can change the parameters of the Haar Cascade to detect the face, nose and mouth in a frame.

<div>
<p float="center">
  <img src="Mask-Detection-using-machine-learning/working screenshots/scale.jpg" alt="Scale" width="350" />
</p>
</div>

* Before running the program install the following modules:-
  * numpy
  * cv2
  * pillow
  * customtkinter
