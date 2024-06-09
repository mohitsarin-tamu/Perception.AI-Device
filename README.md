- Buisness Canvas

Here is the detailed Business Canvas that we proposed for our device.

<img src="Canvas.PNG" alt="i" width="700"/>

- Device 3D Desgin in Blender

<img src="IMG-20181006-WA0054.jpg" alt="i" width="300"/>

- Hardware Overview
![i](PAI2.jpg)

- Software Overview (Algorithmic Flow)
![i](PAI.jpg)

- Image-Processing
Here's the image captured by the camera, which is given as input to the algorithm.
![i](myfinger.jpeg)

The finger is detected and the other regions of the image are masked.
![i](otsu.jpg)

The tip of the finger is detected, identifying the point for the line detection algorithm. The nearby text is processed and passed to the line detection algorithm, enabling the detection of a series of letters, and hence word in the given line.
  
![i](marked.jpg)
![i](selected1.jpg)

![i](adtg.jpg) 

The bounding box is generated, and the words are read and sent to the TTS algorithm for further processing.
![i](BindingBox_latest2.jpg)

Link to TTS functionality in a given example: 






