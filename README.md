# VirtualMouse

>A Mouse on your Finger Tips

## Discription

Virtual Mouse is an **AI-Based Application** that use Hand Gesture to access Mouse Cursor. The Goal of Virtual Mouse is to Manage computers and other devices with gestures rather than pointing, Clicking, or touching the display directly. Virtual Mouse can be used by a person who is not comfortable with touchpad/PhysicalMouse. Additionally, Virtual Mouse can be used in various Games and other AI Applications which dependent on the Controlled through User-Defined Gestures.


Using this Application, One can access the cursor for minimizing screen, maximize the screen, copy, paste, cut, and other functions which can be accessed through Physical Mouse. This Application uses a **Real-Time camera** to detect hand landmarks, tracks gesture patterns made by the User. As soon as the user shows up his hand in the camera the application detects it & draws a bounding box around the hand.Specifically, This Virtual Mouse **detects index Finger and Middle Finger** Movement and acts accordingly. Mouse Cursor can move when Index Finger is up. When the Index finger and Middle Finger both are up and when they are at a specific distance or they are joined together, Click Operation is then Generated.

Virtual Mouse is a Python Application.Virtual Mouse Consist of two python Scripts. One is **pyHandTrackingModule.py** and another is **Mouse.py** . pyHandTrackingModelue tracks the hand gestures, draws hand landmarks and edges. This Module is made of hand Detector Class and findhands(), findPosition(), fingersUp(), findDistance() methods. Mouse.py use the pyHandTrackingModule to detect hand movements and act accordingly. Mouse.py uses a pyautogui package to function as Mouse.

### Python Library Used in Virtual Mouse

**1. OpenCV**
    - OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library that is used for accessing the Real-time      Camera(WebCam), drwing and Image Processing which gives inputs to the Virtual Mouse.
    
**2. Mediapipe**
    - MediaPipe is Google's open-source framework, used for media processing.MediaPipe Hands is a high-fidelity hand and finger tracking solution. It employs machine learning (ML) to infer 21 3D landmarks of a hand.

**3. Pyautogui**
    - PyAutoGUI is a Python automation library used to click, drag,scroll, move, etc. It can be used to click at an exact position. It is used for controlling mouse movement and clicks of Virtual Mouse.

## Demo Video
https://www.youtube.com/watch?v=DUsEfNpS544


### Note: 
- Use One Hand Only to access the Computer
- Use Index finger and Middle Finger Only, for the smooth running of the Application.
- There might be dependency issues that occur while implementing this project. Make Sure to use the Upgraded Python Libraries.
    


