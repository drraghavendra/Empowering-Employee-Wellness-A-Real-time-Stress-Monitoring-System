# Empowering-Employee-Wellness-A-Real-time-Stress-Monitoring-System

The Project objective is to Develop and deploy a real-time stress monitoring system that integrates physiological data (e.g., heart rate variability, skin conductance) with self-reported stress levels to identify and alert employees and designated support personnel (e.g., HR, wellness coaches) to potential stress overload in real-time, facilitating timely intervention and support.

Impact Of the Project 

Reduce employee stress-related absenteeism and presenteeism by 15% within the first year of implementation by enabling proactive interventions based on real-time stress data. This will contribute to a more engaged, productive, and healthier workforce.


Employee Face Emotion-based feedback collection Employee Meeting Participation Detection (Absenteeism detection) We seek to identify and boost the morale of passive employees by collecting information in an unobtrusive manner. We also seek to simplify the attrition process by establishing patterns for employee behavior and activeness. We include 1. Employee-Emotion Based Attrition Prediction 2. Passive Employee Engagement identification using Audio Processing

A Solution for ALL that revolutionizes the Corporate Ecosystem. We aim at overcoming the pitfalls of the human errors prevalent among attrition systems all over the world. We propose to build a fully automated, AI-based system overcoming the challenges in the present systems.

Emotion to Attrition Connection - The concept behind the system is to actively monitor the employee’s emotion levels during login time in the morning. The emotion can then be analyzed to provide further insights regarding his morale. The desired result is achieved using a combination of Image Processing Techniques and Deep Learning Interfaces. The system achieves high accuracy within the given time. Job Satisfaction - can be understood if the employee has a smile for the day's login!

The Audio Processing Suite: We have also built a system that is able to accurately detect and transcript dialogues from meetings using Audio Processing and AI Techniques. The system is able to associate voices with individuals with relative ease, The idea is to track all the employees' engagement in meetings over a period of time and to establish a clear pattern of disengagement. This information can be further used by the organization as appropriate.

# Facial Recognition and Facial Emotion Detection using Flask

Used face-recognition library and OpenCV to **_detect faces_** (from live webcam stream) and allow access into the cells. Simple **_authorisation check_** to further access into your particular cell (unless you are an administrator). Deep convolutional neural network to **_detect emotions_** (from videos) and display a label along with a pie chart containing the result. 

# Data Set and Code links

https://drive.google.com/drive/folders/1aiZCNIXJ0uodEEc6NcbFKWd1bxosrBRT?usp=sharing



## Tools and Libraries used:
- Python - face_recognition - https://pypi.org/project/face-recognition/
- cmake - https://cmake.org/documentation/
- keras - https://keras.io/api/
- dlib - http://dlib.net/python/index.html

_Note:_ You can use Heroku or any other cloud service for the application to run.

## Working:
Here we have a detailed explanation regarding the workflow of the WebApp.
- ### Homepage:
Click on button to move to the Login Page. 

![img.png](README_images/img.png)
- ### Login Page:
Clicking on the button runs the *Facial Recognition* model for access. To add yourself into the list of permitted people, add your image to the `faces/` folder.
Now, you move onto the Cells page.  
*(This page was created so that one can further develop a Sign-Up feature for the WebApp.)* 

![img_1.png](README_images/img_1.png)
![img_2.png](README_images/img_2.png)
- ### Cells Page:
Here, you can only get into the cell of your relative/close friend. This is done so that there is security amongst various cells. If you are an administrator, you are allowed access into every cell.

![img_3.png](README_images/img_3.png)
- ### Cell 9 Page:
I have only attached video for Cell 9 page (as of now), so ensure that you have added yourself to `cell9.txt/`. Once you choose Cell 9, the *Facial Emotion Detection* model runs so the website might take some time to load. Once Cell 9-page opens, click on the button to make the text disappear and a pie chart with the emotional summary appears. 

![img_4.png](README_images/img_4.png)
![img_5.png](README_images/img_5.png)

There are other webpages for Programs, Care, Reviews and Contact pages as well. Clicking on the text at the top right corner on any given webpage, will take you to the respective webpage.

For further understanding, refer to the flow diagram of my website at:
https://drive.google.com/file/d/1y_p29exw_yInqN4lpibHMWQi8DL9cpkY/view?usp=sharing

I have also uploaded a video explaining the workflow of my website at:  
https://drive.google.com/file/d/1UvPXMw64tPMNHWdRshuwQPVvUAJuqse1/view?usp=sharing



## Installation:

Clone the repository and unzip the files. This produces the following folders: `train/` , `test/` , `templates/` , `static/` ,`validation/`, `faces/` contains the images of the people who have access into the cells.`modelh.h5` includes a trained model.

To install all the libraries needed, run `-r requirements.txt`. 

## Instructions:

To start the Flask app, run the python file `app.py`.  
If you want to run from terminal, run the command python `app.py`.


## References:
- Documentation: https://pypi.org/project/face-recognition/
- GitHub repos: https://github.com/akmadan/Emotion_Detection_CNN
- Content for webpage: https://www.sanctumwellness.org/
- Articles referred to: https://www.hindawi.com/journals/complexity/2019/3581419/
