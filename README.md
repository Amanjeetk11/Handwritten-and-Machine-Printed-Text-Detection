## MINI PROJECT | Handwritten and Machine Printed Text Detection
Group No- 14

#### Under supervision of  Dr. Pavan Chakraborty & Dr. Sonali Agrawaal

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#team-members">Team Members</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#How-to-use">How to use</a></li>
    <li>
      <a href="#model-predictions">Model Predictions</a>
      <ul>
         <li><a href="#MIXED INPUT">MIXED INPUT</a></li>
        <li><a href="#CLASSIFIED OUTPUT">CLASSIFIED OUTPUT</a></li>
       
      </ul>
    </li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>


## About The Project

In this project , we are working to archive proper documents or books, starting from sets of short documents with annotations . It is necessary to separate the machine printed and handwritten text before applying different recognition methodologies to each. Because a document image having both types of texts (machine printed and handwritten text) may give rise to significant issues within a digitisation and recognition pipeline. In this project we will strive to figure out handwritten text from machine printed text using the Optical Character Recognition (OCR).

##### Keywords: 
Printed text · Handwritten text · OCR · Shape-based features · GUI


## Team Members
|   Enrollment No.  |   Name   | Github ID |
|   --------------  |   ----   | -------- |
|    IIT2019239  |  Mrityunjaya Tiwari  | [Error404m ](https://github.com/Error404m) |
|    IIT2019222  |   Rauank Singh Rathore  | [Error404r ](https://github.com/Error404r) |
|    IIB2019006  |   Amanjeet Kumar |  [Amanjeetk11 ](https://github.com/Amanjeetk11) |
|    IIT2019202  |   JYOTI VERMA | [Jyo123-verma ](https://github.com/Jyo123-verma) |


## Built With
<ul>
   <li>Flask</li>
   <li>Python</li>
  <li>HTML</li>
  <li>CSS</li>
  <li>Javascript</li>
  <li>python</li>
</ul>


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
  * Create the Virtual Environment
  ```sh
  $ python3 -m venv venv
  ```
  
  * Activate the virtual environment
  ```sh
  $ source venv/bin/activate
  ```
  
  * Install Falsk
  ```sh
  $ pip3 install Flask
  ```
  
  * Install NumPy
  ```sh
  $ python -m pip install numpy
  ```
  
  * Install Pandas
  ```sh
  $ python -m pip install pandas
  ```
  
  * Install Matplotlib
  ```sh
  $ python -m pip install matplotlib
  ```
  
  * Install OpenCV
  ```sh
  $ python -m pip install opencv-python
  ```
  
  * Install Keras
  ```sh
  $ python -m pip install keras
  ```
  
  * Install TensorFlow
  ```sh
  $ python -m pip install tensorflow
  ```
  
 ### Installation


1. Clone the repo
   ```sh
   git clone https://github.com/Amanjeetk11/mini-project.git
   ```
2. Change directory to main file
   ```sh
   cd model_codes
   ```
3. Install requirements.txt
   ```sh
   pip install requirements.txt 
   ```
4. Set the FLASK_APP system variable
   ```sh
   $ export FLASK_APP=app.py
   ```
5. Run Flask
   ```sh
   $ flask run
   ```
Visit http://127.0.0.1:5000 to see your app in action 

<!-- Usage -->
## How to use
1.Go through webpage link http://127.0.0.1:5000 
<br> <img src="https://github.com/Amanjeetk11/mini-project/blob/main/Screen-Shots/website.jpeg"  height="370" />

2. Tap on choose file.
3. Upload or click picture of crops.
4. Click on predict

The system will analyse uploaded picture and give output with classification printed texts (show in blue color), handwritten texts (show in green color) and non-texts (show in yellow color).


<!-- Usage -->
## Model Predictions
 >### MIXEDED INPUT
 > <br> <img src="https://github.com/Amanjeetk11/mini-project/blob/main/Screen-Shots/Mixed_input.jpeg"  height="370" /> 
 > <br>
  
 > ### CLASSIFIED OUTPUT
  
 <br> <img src="https://github.com/Amanjeetk11/mini-project/blob/main/Screen-Shots/Classified_output.jpeg"  height="370" /> <br>
  

 

<!-- Acknowledgements -->
## Acknowledgements
* [Deploy flask app ](https://www.freecodecamp.org/news/how-to-build-a-web-application-using-flask-and-deploy-it-to-the-cloud-3551c985e492/)
* [Flask App tutorial](https://www.digitalocean.com/community/tutorials/how-to-make-a-web-application-using-flask-in-python-3)
* [Training model with Tensorflow](https://towardsdatascience.com/build-your-first-machine-learning-model-using-tensorflow-d61b9b2b7d5e)
* [deploy model using Keras](https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/)


