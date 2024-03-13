<h1 align=center>Hand-Controlled-AI-Virtual-Mouse 🖱️👆</h1>
<h2 align=center>Version : 1.0.0.1</h2>
<!--This is an AI based Virtual Mouse controlled by our hand gestures and hand detection.-->

<img src="https://user-images.githubusercontent.com/95229816/185941431-83ba8fc6-0863-4a9b-a8ef-9908a29bd9ba.png">

<u><h2>The mouse is the one of the wonderfull inventions of the Human Computer Interaction(HCI) Technology.</h2></u>
<h3>Currently we are using wired or may be wireless mouses,In real time cases some computers may not support for a physical mouse or may some users may cannot use physical mouse, so this Hand controlled AI Virtual Mouse can be used to overcome this problem. Making a user to control the mouse by reducing the computer human interaction.</h3>

<h1>FUNCTIONALITIES:</h1>
<h4> -> This was built using the openCV-python and mediapipe for Detecting and processing the image and mediapipe an open source cross-platform developed by google for media processing and ready-to-use ML solutions for computer vision tasks.</h4>
<h4> -> Our Hand Controlled Virtual mouse can able to move the mouse anywhere on the screen and can able to perform the click operation.</h4>
<h4> -> Our Index finger can be used to move the mouse over the screen.</h4>
<h4> -> When Our Index finger and Thumb come close to each other or touch each other then it performs the click operation.</h4>
<h4> -> And the PyautoGUI for programmatically control the mouse and keyboard.</h4>


<h2>Now coming to the code part </h2>
The Libraries that need to be installed are written in the requirements.txt file

```text
opencv-python - 4.6.0.66
numpy - 1.23.1
matplotlib - 3.5.2
mediapipe - 0.8.10.1
pyautogui - 0.9.53
pillow - 9.2.0
```

### Install the following necessary pip
```sh
pip install opencv-python
pip install numpy
pip install matplotlib
pip install mediapipe
pip install PyautoGUI
pip install PIL
```

### The actual working of the mouse is based on the Hand Landmarks which can be viewed and controlled by opencv and mediapipe.
### Our hand contains a total of 21 landmarks.
![hand_landmarks](https://user-images.githubusercontent.com/95229816/186465439-9253c685-9561-474d-aa79-5e5baa874256.png)

<h1>Checkout the Demo Below : 👇</h1>
<h4>At First The mouse pointer movement is very bad and horrible to see so, I have added a **smoothening** factor that makes the mouse pointer move like a feather. </h4>

```python
smoothening = 9
clocx = plocx + (index_x - plocx) /smoothening
clocy = plocy + (index_y - plocy) /smoothening
# you can multiply or divide with the smotthening
```

<h3>If any necessary commits are required to increase the elegance of this repo! i'm always open for a PR.</h3>

### <h2>With this signing off..!!,BHARATH GUNTREDDI ..🤞</h2>

<video controls autplay muted src="https://user-images.githubusercontent.com/95229816/186448935-4ab29a18-92eb-4e71-ad99-fd8970ee12d6.mp4" />


