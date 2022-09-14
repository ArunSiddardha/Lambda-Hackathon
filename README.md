<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
 
  <h1 align="center">Face Recognition Demonstration</h1>

</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#introduction">Introduction</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#how-to-use">How to Use</a>
    </li>
    <li>
      <a href="#key-features">Key Features</a>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Introduction

This project is built under lambda hackathon.



<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

This project is built using.

- Python : Server Side  Framework
- Flask : Backend Framework
- SQLALchemy : Database
- DeepFace : Face Recognition
- RetinaFace : Face Detection 


<!-- GETTING STARTED -->
## How to use

- Install python version 3.8
```sh
  sudo apt-get install python3.8
  ```

- Clone this repository
```sh
  git clone https://github.com/ArunSiddardha/Lambda-Hackathon.git
  ```
- Change the working directory
```sh
  cd Lambda-Hackathon
  ```
- Create a python virtual environment in the working directory

```sh
    python3 -m venv myenv
```

- Activate the python Virtual environment

```sh
    source myenv/bin/activate
```
- Install all the required packages

```sh
    pip3 install -r requirements.txt
```


- Run the flask server (using anyone of the command)
```sh
    python app.py  or flask run 
```
- Run the app on the browser
```sh
    http://localhost:8000/ or whatever port it gives 
```


<p align="right">(<a href="#top">back to top</a>)</p>


## Key Features

### Tracking Attendance
- Course Registration
    - Students have to register for the course using their roll No and their face
- Taking Attendance
    - Teachers can take attendance using this portal and the attendance gets marked in the attendance sheet
- Classroom Strength
    - Teachers can upload the pic of their classroom of their course and get the strenght present on the class room on a particular day
- Checking Attendance
    - Teachers can check the class strength and the students attendance using this portal
## Images of the Web Application
### Home Page

<img src="ourapp/static/ReadmeImages/Attendance1.png" alt="Logo">
<img src="ourapp/static/ReadmeImages/Attendance2.png" alt="Logo">
<br>
<br>

### Class Attendance Portal


- Class registration
<img src="ourapp/static/ReadmeImages/class1.png" alt="Logo">

- Taking the Attendance
<img src="ourapp/static/ReadmeImages/takeattendance.png" alt="Logo">

- Getting the class strength
<img src="ourapp/static/ReadmeImages/class3.png" alt="Logo">



<p align="right">(<a href="#top">back to top</a>)</p>
