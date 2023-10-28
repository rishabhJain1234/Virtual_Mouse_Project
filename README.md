# AI Virtual Mouse Using Hand Gesture Recognition

## Why do we use the virtual mouse?
The proposed AI virtual mouse system can be used to overcome problems in the real world such as situations where there is no space to use a physical mouse and also for persons who have problems in their hands and are not able to control a physical mouse. Also, amidst the COVID-19 situation, it is not safe to use the devices by touching them because it may result in a possible situation of the spread of the virus by touching the devices, so the proposed AI virtual mouse can be used to overcome these problems since hand gestures and hand Tip detection is used to control the PC mouse functions by using a webcam or a built-in camera.

## Algorithm Used for Hand Tracking
For the purpose of detecting hand gestures and hand tracking, the MediaPipe framework is used, and the OpenCV library is used for computer vision. The algorithm makes use of machine learning concepts to track and recognize hand gestures and hand tips.


## Logic Flow
![ye](https://github.com/AggarwalManav/Virtual_Mouse_Project/assets/127924433/9d0456d9-003f-4158-94e6-dd97e8e7bb9d)



## Controls:
### 1.Movement
![movement](https://github.com/AggarwalManav/Virtual_Mouse_Project/assets/127924433/d67de6de-2d51-475f-8b24-306a7d5cc7d3)

### 2.Left Click
![left_click](https://github.com/AggarwalManav/Virtual_Mouse_Project/assets/127924433/1170de24-f863-458c-bf0a-be1e60efa19d)


### 3.Right Click
![right_click](https://github.com/AggarwalManav/Virtual_Mouse_Project/assets/127924433/4b3cec35-7a24-476f-8062-e2775538421a)


### 4.Double Click
![double_click](https://github.com/AggarwalManav/Virtual_Mouse_Project/assets/127924433/28a6dee5-7fb6-49bd-a7a2-e92145b765a8)


### 5.Scroll Up
![scroll_up](https://github.com/AggarwalManav/Virtual_Mouse_Project/assets/127924433/5cc619e9-2d78-4084-9acf-5a0fe99eaa78)


### 5.Scroll Down
![scroll_down](https://github.com/AggarwalManav/Virtual_Mouse_Project/assets/127924433/1f96d793-231c-45d4-a774-b5e1083b6fa2)


### 7.Drag and Drop
![drag_and_drop](https://github.com/AggarwalManav/Virtual_Mouse_Project/assets/127924433/6cf40e66-9665-46ca-9aa5-34180e20c899)

## Challenges we ran into
1.Finding alternatives to depriciated libraries:<br>
In the ever evolving world of AI-ML, the breakthrough in new technologies and updation comes at the cost of depreciated and incompatible libraries.Like we tried to use autopy library for cursor control but due to its incombatible nature, we ran into several issues.Ultimately we switched to pyautogui and ctypes.<br>

2.Deployment issues:<br>
We tries to convert our .ipynb (or.py) file into .exe file using pyinstaller but it was constantly giving us error due to its incompatibility with mediapipe.We even tried to git clone mediapipe where our .exe was installed but that too didn't work.Later we tried the same process with auto-py-to-exe but even that gave us the same error.<br>

3.Running out of usable hand gestures:<br>
This project required us to constantly look for new and custom hand gestures which would be easy to be picked by the mediapipe model.<br>




## Major applications:
1.Accessibility Solutions: Virtual mice make it easier for individuals with mobility impairments to interact with computers, promoting digital inclusivity.<br>

2.Ergonomic Computing: They reduce the risk of repetitive strain injuries by allowing users to operate computers without physical devices, promoting healthier postures.<br>

3.Hygienic Interfaces: In healthcare, public spaces, and shared work environments, virtual mice offer contactless control, reducing the risk of spreading infections.<br>

4.Precision Tasks: They excel in tasks requiring pinpoint accuracy, such as graphic design and medical imaging, providing enhanced control and precision.<br>

5.Multimodal Interaction: Virtual mice seamlessly integrate hand gestures, facial expressions, and voice commands, enhancing the computing experience and offering versatility.<br>

6.Gesture-Based Computing: Ideal for non-verbal communication, they are used in presentations, virtual reality, and gaming for intuitive, hands-free control.<br>

7.Cost-Effective Accessibility: Virtual mice are a cost-effective alternative for those who require advanced input methods, addressing financial barriers to technology access.<br>

8.Privacy and Security: They enhance data security by reducing the risk of leaving personal information behind and may offer biometric authentication through facial recognition.<br>

9.Adaptability to User Preferences: Users can customize their virtual mouse experience to match their unique needs and preferences.<br>

10.Collaborative and Remote Work: Virtual mice facilitate interactive and hygienic collaborative and remote work, enabling control without physical contact and improving communication in shared workspaces and virtual meetings.<br>

These applications highlight the versatility and potential impact of virtual mice in various domains of technology and human-computer interaction.<br>







## Conclusions
From the results of the model, we can come to the conclusion that the proposed AI virtual mouse system has performed very well and has greater accuracy compared to the existing models, and also the model overcomes most of the limitations of the existing systems. Since the proposed model has greater accuracy, the AI virtual mouse can be used for real-world applications, and also, it can be used to reduce the spread of COVID-19, since the proposed mouse system can be used virtually using hand gestures without using the traditional physical mouse.




