---
title: "[New] Unveiling Hand Tracking's Evolution and Practice for 2024"
date: 2024-09-11T05:15:10.004Z
updated: 2024-09-12T05:15:10.004Z
tags: 
  - screen-recording
  - ai video
  - ai audio
  - ai auto
categories: 
  - ai
  - screen
description: "This Article Describes [New] Unveiling Hand Tracking's Evolution and Practice for 2024"
excerpt: "This Article Describes [New] Unveiling Hand Tracking's Evolution and Practice for 2024"
keywords: "\"Hands Tracker History,Tracking Tech Advance,Hand Gesture Control,Touchless Interaction,Motion Capture Evolution,Kinesthetic Input Devices,Real-Time Gesture Analysis\""
thumbnail: https://thmb.techidaily.com/c196f6b4394e95f28b75708e950be08411857a7cc6fdf0b1b999475eb2576da4.jpg
---

## Unveiling Hand Tracking's Evolution and Practice

In the era of advancements, **Hand Tracking** is a fascinating technology with a great range of applications in both virtual and augmented reality.

**Hand Tracking** is a process by which a computer can analyze and interpret the movement of a person's hands. This can be done using various devices, such as smart gloves, often known as data gloves.

In this article, we’ll discuss **Hand Tracking** technology, its various applications, and how to create it using Python, OpenCV, and Media Pipe.

1. [Tracking With Interface](#part2-1)
2. [Tracking Without Interface](#part2-2)

* [Using Python, OpenCV, And MediaPipe To Create A Hand Tracking](#part3)  

1. [What is OpenCV](#part3-1)  
2. [What Is Media Pipe](#part3-2)  
3. [Guidance With Steps](#part3-3)

* [Use Filmora to demonstarte your Hand Tracking skill](#part4)


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>



## Part 1\. What Is Hand Tracking? Where Is It Applied?

Hand Tracking refers to the process of tracking the position and movement of a user's hands in virtual reality. This is usually done using a combination of sensors, including cameras, infrared sensors, or ultrasonic sensors.

By tracking the user's hands, VR systems can provide more immersive and interactive experiences. For example, Hand Tracking can be used to allow users to interact with virtual objects, as well as to provide input for gestures and body language.

The Oculus Quest 2 is a virtual reality headset that immerses you in virtual worlds. Quest 2's one of the coolest features is Hand Tracking, which lets you interact with the virtual world around you using your hands.

With Hand Tracking, you can interact with the virtual world more naturally and intuitively. You can use your hands to pick up objects, draw, and even type on a virtual keyboard. Moreover, it opens up new possibilities for gameplay, allowing you to play games in new and innovative ways.

![hand tracking technology](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-technology.jpg)





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130889/7443" target="_top" id="2130889">
  <img src="//a.impactradius-go.com/display-ad/7443-2130889" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130889/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Part 2\. Types Of Hand Tracking

There are two main types of Hand Tracking: with interface and without interface:





<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123467/16836" target="_top" id="2123467">
  <img src="//a.impactradius-go.com/display-ad/16836-2123467" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123467/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




### Tracking With Interface

With interface Hand Tracking, you need to use a device such as a glove or a controller to interact with the virtual world. This can be used in VR or AR applications. It is further divided into two systems:

**1\. Inertial Motion Capture Gloves**

Inertial motion capture gloves use sensors Inertial Measurement Units or IMUs with built-in sensors to track the movement of your hands. These sensors include gyroscopes, accelerometers, and sometimes magnetometers for measuring angular rate, detecting gravitational force and acceleration, and measuring the earth’s magnetic field, respectively.

These gloves can be used for a variety of purposes, such as gaming, virtual reality, and motion capture for movies and video games. Inertial motion capture gloves are becoming increasingly popular as they offer a more immersive experience than traditional controllers.

**2\. Optical Motion Capture Systems**

Optical motion capture is a process that uses cameras and reflective sensors to track movement in three-dimensional space. These systems are often used in movies and video games to create realistic animations.

Optical motion capture systems emit infrared light from the camera. The markers reflect light, which is then captured by cameras. The movement of the markers is then used to create a three-dimensional model of the object.

The more cameras used, the more accurate the results. While this technology is very precise, it can be limited by factors such as body position and movement.

### Tracking Without Interface

Also known as Markerless Hand Tracking, this type of Hand Tracking allows users to track their hand movements without the need for any external markers or data gloves, meaning more spontaneous interaction and freedom of movement. This could hugely impact everything from gaming to virtual reality to human-computer interaction.

Right now, markerless Hand Tracking is still in its early stages, with a few limitations. However, as this technology continues to develop, we will likely see more and more applications for it in the future.

## Part 3\. Using Python, OpenCV, And MediaPipe To Create A Hand Tracking

Above we have learned what is Hand Tracking and the two types of it. Now let’s see how we can create a hand tracking with two Python Libraries - OpenCV and MediaPipe.

Before we go further about them, let us learn about Python quickly. Python is a versatile language used for a wide range of tasks, including image processing and computer vision. We will use Python and two Python Libraries: OpenCV and MediaPipe, to create a Hand Tracking module.





<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139120/17108" target="_top" id="2139120">
  <img src="//a.impactradius-go.com/display-ad/17108-2139120" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139120/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




### What is OpenCV

To get a deeper understanding of OpenCV, please read our article: _Opencv Tracking, a compete review_.（同期交付文章，请插入相关内链\~）

### What Is Media Pipe

Media Pipe is an open-source framework by Google that provides a set of tools for working with multimedia data or media processing. It includes modules for handling audio, video, and images. Media Pipe also supports various codecs and file formats.

There are two stages for creating a Hand Tracking program using MediaPipe:

1. **Palm Detection**: In the first stage, MediaPipe has to work with the entire input image, providing a cropped image of the hand.
2. **Hand Landmarks Identification**: In the second stage, the framework works with the cropped image of the hand to find 21 hand landmarks.

![20 hand landmarks for identifiction – hand tracking](https://images.wondershare.com/filmora/article-images/2022/07/20-hand-landmarks-for-identifiction-hand-tracking.jpg)





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135473/26400" target="_top" id="2135473">
  <img src="//a.impactradius-go.com/display-ad/26400-2135473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135473/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




### Guidance With Steps

Before starting to create Hand Tracking, you need to install the [Pycharm IDE](https://www.jetbrains.com/pycharm/download/#section=windows)app on your PC. Once installed, launch it and follow these instructions step-by-step:

**Install OpenCV and MediaPipe**

Click the **“New Project”** option and select **“Create”** on the next Window. Open the **Terminal** to install the two libraries.

![install and launch the pycharm app on your pc](https://images.wondershare.com/filmora/article-images/2022/07/install-and-launch-the-pycharm-app-on-your-pc.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115928/19272" target="_top" id="2115928">
  <img src="//a.impactradius-go.com/display-ad/19272-2115928" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115928/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




Copy and paste the following command in the **Terminal** to install **OpenCV:**

![copy and paste command to install opencv](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-1.jpg)





<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




Now, to install **MediaPipe**, copy and paste the following command:

![install mediapipe](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-2.jpg)

**Coding**

A _main.py_ file for writing code will be automatically created in _Pycharm_ app once you create a new project.

##### Step1 Importing The Libraries

First, import the OpenCV and MediaPipe to use their dependencies. Once done, create an object _cap_ for video capturing and three other objects; _mpHands, hands,_ and _mpDraw_ to manipulate your input using MediaPipe.

![importing the libraries](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-3.jpg)





<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123471/16836" target="_top" id="2123471">
  <img src="//a.impactradius-go.com/display-ad/16836-2123471" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123471/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




##### Step2 Capturing And Processing An Image Input

Copy and paste the following line of code to take the image input from your PC webcam.

![capturing and processing an image input](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-4.jpg)

The image is converted to RGB from BGR because MediaPipe works with this type of image. The RBG image is then processed to track the hand.

##### Step3 Working With Both Hands

Now, create a class for tracking and for the hands function to work, key in the basic parameters. Next, provide all the initialization required. This includes the basic parameters and MediaPipe initializations. Put _“self”_ before each object to provide access to its attributes and methods.

![working with both hands](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-5.jpg)

##### Step4 Creating Method For Tracking Hands In Input Image

![creating method for tracking hands](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-6.jpg)





<!-- affiliate ads begin -->
<span id="1983588">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983588.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983588">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983588.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983588%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983588/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




Afterward, use the above code to create a method for using specifically to identify hands in the input image. The code will also draw hand landmarks and hand connections.

##### Step5 Locate The ‘X’ and ‘Y’ Coordinates Of Each Hand Point

To create a method for finding the x and y coordinates of the z21 hand points and a list that you will use to keep the values of these, write the code below:

![locate x and y coordinate of hand point](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-7.jpg)

In this method, use the code that you used to find the ID and hand landmark of each hand point. Moreover, put the code you will use to circle the hand point.

##### Step6 Main Method

Now, write the below dummy code to showcase what the module can do, i.e., identify and track hands. The code appears in the main method and uses the _lmlist object_ and _image_.

![](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-8.jpg)





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137379/7443" target="_top" id="2137379">
  <img src="//a.impactradius-go.com/display-ad/7443-2137379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




##### Step7 Main Method Execution

To execute the main method, copy and paste the following code lines:

![main method execution](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-9.jpg)

##### Step8 Result

The module and output of the program will be the same, and when they are complete without any errors, you will get your output, i.e., the module will track and identify your hand movements without any glitches.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123727/7443" target="_top" id="2123727">
  <img src="//a.impactradius-go.com/display-ad/7443-2123727" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123727/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Part 4\. Use Filmora to demonstarte your Hand Tracking skill

After what has been explained above and what you have learned by now, we hope you have been equipped with hand tracking module knowledge and be ready to take action. Here, we will also sincerely recommend you a user-friendly and professional video edtior to show your hand motion scene – [Filmora](https://tools.techidaily.com/wondershare/filmora/download/)!

[Filmora](https://tools.techidaily.com/wondershare/filmora/download/) is available for all types of users. You can easily use it to edit your video, add effects to it and insert your hand motion part naturally.

Learn more about Filmora:

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For Win 7 or later(64-bit)

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For macOS 10.14 or later





<!-- affiliate ads begin -->
<span id="1975555">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975555.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975555">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975555.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975555%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975555/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Conclusion

In this article, we’ve explored Hand Tracking and its two types, i.e., tracking with interface and tracking without interface. Moreover, we provided step-by-step guidance on using Python, OpenCV, and MediaPipe to create a Hand Tracking module.

We hope this guide helped resolve your queries, and you can now create a Hand Tracking module in no time. And please do try [Filmora](https://tools.techidaily.com/wondershare/filmora/download/) to create a magical video with your Hand Tracking scenes in it!

* [What is OpenCV](#part3-1)
* [What Is Media Pipe](#part3-2)
* [Guidance With Steps](#part3-3)
* [Use Filmora to demonstarte your Hand Tracking skill](#part4)





<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Part 1\. What Is Hand Tracking? Where Is It Applied?

Hand Tracking refers to the process of tracking the position and movement of a user's hands in virtual reality. This is usually done using a combination of sensors, including cameras, infrared sensors, or ultrasonic sensors.

By tracking the user's hands, VR systems can provide more immersive and interactive experiences. For example, Hand Tracking can be used to allow users to interact with virtual objects, as well as to provide input for gestures and body language.

The Oculus Quest 2 is a virtual reality headset that immerses you in virtual worlds. Quest 2's one of the coolest features is Hand Tracking, which lets you interact with the virtual world around you using your hands.

With Hand Tracking, you can interact with the virtual world more naturally and intuitively. You can use your hands to pick up objects, draw, and even type on a virtual keyboard. Moreover, it opens up new possibilities for gameplay, allowing you to play games in new and innovative ways.

![hand tracking technology](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-technology.jpg)





<!-- affiliate ads begin -->
<span id="1983475">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983475.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983475">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983475.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983475%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983475/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Part 2\. Types Of Hand Tracking

There are two main types of Hand Tracking: with interface and without interface:

### Tracking With Interface

With interface Hand Tracking, you need to use a device such as a glove or a controller to interact with the virtual world. This can be used in VR or AR applications. It is further divided into two systems:

**1\. Inertial Motion Capture Gloves**

Inertial motion capture gloves use sensors Inertial Measurement Units or IMUs with built-in sensors to track the movement of your hands. These sensors include gyroscopes, accelerometers, and sometimes magnetometers for measuring angular rate, detecting gravitational force and acceleration, and measuring the earth’s magnetic field, respectively.

These gloves can be used for a variety of purposes, such as gaming, virtual reality, and motion capture for movies and video games. Inertial motion capture gloves are becoming increasingly popular as they offer a more immersive experience than traditional controllers.

**2\. Optical Motion Capture Systems**

Optical motion capture is a process that uses cameras and reflective sensors to track movement in three-dimensional space. These systems are often used in movies and video games to create realistic animations.

Optical motion capture systems emit infrared light from the camera. The markers reflect light, which is then captured by cameras. The movement of the markers is then used to create a three-dimensional model of the object.

The more cameras used, the more accurate the results. While this technology is very precise, it can be limited by factors such as body position and movement.

### Tracking Without Interface

Also known as Markerless Hand Tracking, this type of Hand Tracking allows users to track their hand movements without the need for any external markers or data gloves, meaning more spontaneous interaction and freedom of movement. This could hugely impact everything from gaming to virtual reality to human-computer interaction.

Right now, markerless Hand Tracking is still in its early stages, with a few limitations. However, as this technology continues to develop, we will likely see more and more applications for it in the future.

## Part 3\. Using Python, OpenCV, And MediaPipe To Create A Hand Tracking

Above we have learned what is Hand Tracking and the two types of it. Now let’s see how we can create a hand tracking with two Python Libraries - OpenCV and MediaPipe.

Before we go further about them, let us learn about Python quickly. Python is a versatile language used for a wide range of tasks, including image processing and computer vision. We will use Python and two Python Libraries: OpenCV and MediaPipe, to create a Hand Tracking module.

### What is OpenCV

To get a deeper understanding of OpenCV, please read our article: _Opencv Tracking, a compete review_.（同期交付文章，请插入相关内链\~）

### What Is Media Pipe

Media Pipe is an open-source framework by Google that provides a set of tools for working with multimedia data or media processing. It includes modules for handling audio, video, and images. Media Pipe also supports various codecs and file formats.

There are two stages for creating a Hand Tracking program using MediaPipe:

1. **Palm Detection**: In the first stage, MediaPipe has to work with the entire input image, providing a cropped image of the hand.
2. **Hand Landmarks Identification**: In the second stage, the framework works with the cropped image of the hand to find 21 hand landmarks.

![20 hand landmarks for identifiction – hand tracking](https://images.wondershare.com/filmora/article-images/2022/07/20-hand-landmarks-for-identifiction-hand-tracking.jpg)





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




### Guidance With Steps

Before starting to create Hand Tracking, you need to install the [Pycharm IDE](https://www.jetbrains.com/pycharm/download/#section=windows)app on your PC. Once installed, launch it and follow these instructions step-by-step:

**Install OpenCV and MediaPipe**

Click the **“New Project”** option and select **“Create”** on the next Window. Open the **Terminal** to install the two libraries.

![install and launch the pycharm app on your pc](https://images.wondershare.com/filmora/article-images/2022/07/install-and-launch-the-pycharm-app-on-your-pc.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




Copy and paste the following command in the **Terminal** to install **OpenCV:**

![copy and paste command to install opencv](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-1.jpg)

Now, to install **MediaPipe**, copy and paste the following command:

![install mediapipe](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-2.jpg)





<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139110/17108" target="_top" id="2139110">
  <img src="//a.impactradius-go.com/display-ad/17108-2139110" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139110/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




**Coding**

A _main.py_ file for writing code will be automatically created in _Pycharm_ app once you create a new project.

##### Step1 Importing The Libraries

First, import the OpenCV and MediaPipe to use their dependencies. Once done, create an object _cap_ for video capturing and three other objects; _mpHands, hands,_ and _mpDraw_ to manipulate your input using MediaPipe.

![importing the libraries](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-3.jpg)

##### Step2 Capturing And Processing An Image Input

Copy and paste the following line of code to take the image input from your PC webcam.

![capturing and processing an image input](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-4.jpg)

The image is converted to RGB from BGR because MediaPipe works with this type of image. The RBG image is then processed to track the hand.

##### Step3 Working With Both Hands

Now, create a class for tracking and for the hands function to work, key in the basic parameters. Next, provide all the initialization required. This includes the basic parameters and MediaPipe initializations. Put _“self”_ before each object to provide access to its attributes and methods.

![working with both hands](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-5.jpg)

##### Step4 Creating Method For Tracking Hands In Input Image

![creating method for tracking hands](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-6.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




Afterward, use the above code to create a method for using specifically to identify hands in the input image. The code will also draw hand landmarks and hand connections.

##### Step5 Locate The ‘X’ and ‘Y’ Coordinates Of Each Hand Point

To create a method for finding the x and y coordinates of the z21 hand points and a list that you will use to keep the values of these, write the code below:

![locate x and y coordinate of hand point](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-7.jpg)

In this method, use the code that you used to find the ID and hand landmark of each hand point. Moreover, put the code you will use to circle the hand point.

##### Step6 Main Method

Now, write the below dummy code to showcase what the module can do, i.e., identify and track hands. The code appears in the main method and uses the _lmlist object_ and _image_.

![](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-8.jpg)

##### Step7 Main Method Execution

To execute the main method, copy and paste the following code lines:

![main method execution](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-9.jpg)

##### Step8 Result

The module and output of the program will be the same, and when they are complete without any errors, you will get your output, i.e., the module will track and identify your hand movements without any glitches.

## Part 4\. Use Filmora to demonstarte your Hand Tracking skill

After what has been explained above and what you have learned by now, we hope you have been equipped with hand tracking module knowledge and be ready to take action. Here, we will also sincerely recommend you a user-friendly and professional video edtior to show your hand motion scene – [Filmora](https://tools.techidaily.com/wondershare/filmora/download/)!

[Filmora](https://tools.techidaily.com/wondershare/filmora/download/) is available for all types of users. You can easily use it to edit your video, add effects to it and insert your hand motion part naturally.

Learn more about Filmora:

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For Win 7 or later(64-bit)

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For macOS 10.14 or later





<!-- affiliate ads begin -->
<span id="1834903">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834903.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834903">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834903.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834903%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834903/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Conclusion

In this article, we’ve explored Hand Tracking and its two types, i.e., tracking with interface and tracking without interface. Moreover, we provided step-by-step guidance on using Python, OpenCV, and MediaPipe to create a Hand Tracking module.

We hope this guide helped resolve your queries, and you can now create a Hand Tracking module in no time. And please do try [Filmora](https://tools.techidaily.com/wondershare/filmora/download/) to create a magical video with your Hand Tracking scenes in it!

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>






<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-perfect-online-shopping-picks-for-one-of-a-kind-box-packaging/"><u>[New] 2024 Approved Perfect Online Shopping Picks for One-of-a-Kind Box Packaging</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-trim-videos-with-flair-in-windows-11-photo-apps/"><u>[New] 2024 Approved Trim Videos with Flair in Windows 11 Photo Apps</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-ideal-photo-and-video-shows-on-latest-iphone-models-xr-ios12-for-2024/"><u>[New] Ideal Photo & Video Shows on Latest iPhone Models (XR-iOS12) for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-inspire-chuckles-designing-memes-on-kapwing/"><u>[New] In 2024, Inspire Chuckles – Designing Memes on Kapwing</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-room-prep-101-ensuring-your-system-is-ready-for-oculus-rift/"><u>[New] In 2024, Room Prep 101 Ensuring Your System Is Ready for Oculus Rift</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-top-strategies-for-zoom-use-with-a-chrome-os-device/"><u>[New] In 2024, Top Strategies for Zoom Use with a Chrome OS Device</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unveiling-potential-pro-guide-to-crafting-youtube-videos/"><u>[New] Unveiling Potential Pro Guide to Crafting YouTube Videos</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-amplifying-tiktok-videos-using-zoom-settings/"><u>[Updated] 2024 Approved Amplifying TikTok Videos Using Zoom Settings</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-core-elements-of-virtual-tale-transmission/"><u>[Updated] 2024 Approved Core Elements of Virtual Tale Transmission</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-direct-upload-how-to-share-your-favorite-fb-vids-in-chats/"><u>[Updated] 2024 Approved Direct Upload How To Share Your Favorite FB Vids in Chats</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-how-to-profit-on-tiktok-the-8-essential-steps-you-need/"><u>[Updated] 2024 Approved How to Profit on TikTok The 8 Essential Steps You Need</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-unveiling-magix-video-pro-x-capabilities/"><u>[Updated] 2024 Approved Unveiling Magix Video Pro X Capabilities</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-flair-and-finesse-in-your-gaming-youtube-channel/"><u>[Updated] Flair and Finesse in Your Gaming YouTube Channel</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-enhanced-video-editing-suites-on-windows/"><u>[Updated] In 2024, Enhanced Video Editing Suites on WIndows</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-free-and-fantastic-the-top-10-lut-sources/"><u>[Updated] In 2024, Free & Fantastic The Top 10 LUT Sources</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-visualedge-7-3-elite-image-amplification/"><u>[Updated] In 2024, VisualEdge 7-3 Elite Image Amplification</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-leading-20-zero-copyright-pubg-image-collections-for-2024/"><u>[Updated] Leading 20 Zero-Copyright PUBG Image Collections for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-mastering-the-art-of-using-telegram-online-for-2024/"><u>[Updated] Mastering the Art of Using Telegram Online for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-mastering-visual-impact-a-comprehensive-guide-to-zooms-video-filters-for-2024/"><u>[Updated] Mastering Visual Impact A Comprehensive Guide to Zoom's Video Filters for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-quick-guide-shrinking-and-changing-iphone-video-dimensions-for-2024/"><u>[Updated] Quick Guide Shrinking & Changing iPhone Video Dimensions for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-social-media-video-to-music-conversion-guide-for-2024/"><u>[Updated] Social Media Video to Music Conversion Guide for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-your-blueprint-for-downloading-youtube-srt-in-3-steps-for-2024/"><u>[Updated] Your Blueprint for Downloading YouTube SRT in 3 Steps for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ing-a-bull-or-bear-best-stock-vids-on-youtube/"><u>Becoming a Bull or Bear Best Stock Vids on YouTube</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-video-speed-controller-extensions-a-complete-guide/"><u>Best Video Speed Controller Extensions | A Complete Guide|</u></a></li>
<li><a href="https://activate-lock.techidaily.com/best-ways-to-bypass-icloud-activation-lock-from-apple-iphone-11ipadipod-by-drfone-ios/"><u>Best Ways to Bypass iCloud Activation Lock from Apple iPhone 11/iPad/iPod</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/bring-your-memories-to-life-how-to-make-a-dvd-with-movie-making-software-for-2024/"><u>Bring Your Memories to Life How to Make a DVD with Movie Making Software for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/designers-delight-incorporating-fonts-into-ae-projects/"><u>Designer's Delight Incorporating Fonts Into AE Projects</u></a></li>
<li><a href="https://facebook.techidaily.com/dissecting-the-contentious-facebook-papers/"><u>Dissecting the Contentious Facebook Papers</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-unique-ways-to-personalize-your-phones-physical-appearance-why-stop-at-just-the-screen/"><u>Exploring Unique Ways to Personalize Your Phone’s Physical Appearance: Why Stop at Just the Screen?</u></a></li>
<li><a href="https://fox-info.techidaily.com/guide-to-spotify-ads-learn-how-to-successfully-advertise-on-spotify/"><u>Guide to Spotify Ads - Learn How to Successfully Advertise on Spotify</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-xiaomi-redmi-13c-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Xiaomi Redmi 13C to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-speedy-shot-techniques-to-boost-home-filmmaking/"><u>In 2024, Speedy Shot Techniques to Boost Home Filmmaking</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-the-social-spectacle-10-tweets-to-watch/"><u>In 2024, The Social Spectacle 10 Tweets To Watch</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-top-10-best-meme-templates/"><u>In 2024, Top 10 Best Meme Templates</u></a></li>
<li><a href="https://driver-download.techidaily.com/install-faster-graphics-performance-now-with-nvidia-game-ready-driver/"><u>Install Faster Graphics Performance Now with Nvidia Game Ready Driver</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quick-steps-to-fresh-drivers-for-your-amd-ryzen-5-2500u-processor/"><u>Quick Steps to Fresh Drivers for Your AMD Ryzen 5 지구맥스 2500U Processor</u></a></li>
<li><a href="https://extra-information.techidaily.com/quickening-speed-of-slide-show-media-playback/"><u>Quickening Speed of Slide Show Media Playback</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolving-connection-problems-making-your-seagate-external-work-with-windows-11/"><u>Resolving Connection Problems: Making Your Seagate External Work with Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/revive-your-bricked-iphone-in-just-four-simple-steps/"><u>Revive Your Bricked iPhone in Just Four Simple Steps</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/the-journey-through-timeran-images-3-methods-on-facebook-for-2024/"><u>The Journey Through Time'ran Images 3 Methods on Facebook for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-tutorial-on-leveraging-google-gemini-effectively/"><u>The Ultimate Tutorial on Leveraging Google Gemini Effectively</u></a></li>
<li><a href="https://fox-info.techidaily.com/transform-your-vision-into-reality-essential-movies-maker-skills-on-windows-8/"><u>Transform Your Vision Into Reality Essential Movies Maker Skills on Windows 8</u></a></li>
<li><a href="https://fox-info.techidaily.com/unlocking-full-potential-with-final-cut-pro-for-2024/"><u>Unlocking Full Potential with Final Cut Pro for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-poco-m6-pro-5g-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Poco M6 Pro 5G Users</u></a></li>
</ul></div>




