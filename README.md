Cone Detection Project
This repository contains the code and resources for a cone detection system implemented using YOLOv5. The project is designed to identify cones in video footage, which is particularly useful for applications such as autonomous driving tests and robotics navigation.

Description
This project leverages the YOLOv5 object detection model to detect cones in a video file. The video is processed frame by frame, with the model identifying and bounding potential cones. This approach provides a robust method for real-time object detection, which can be integrated into larger systems for dynamic environment tracking and navigation.

System Requirements
Operating System: This project was developed on Google Colab, which provides a hosted Jupyter notebook service that includes Python 3.7 and a managed environment. Google Colab runs on a Linux-based VM, so the project is Linux-compatible.
Python Version: Python 3.7 or later.

NOTE :: before cloning the repository download fsd1.mp4 that us un the repository video on your local machine (github does not work well with large videos)

Installation Instructions :


Step 1: Set Up Your Environment
This project is designed to run in Google Colab, which requires no local setup for Python and dependencies as Colab provides a pre-configured environment.
Access Google Colab: Go to Google Colab and sign in with your Google account.

Step 2: Clone the Repository
You can clone the repository directly into Google Colab using the following commands:
!git clone https://github.com/nasirfaisal83/con-Detection.git
%cd yourrepositoryname

Step 3: Install Required Libraries
Though most dependencies are pre-installed in Colab, ensure all required libraries are up-to-date:
!pip install torch torchvision torchaudio --upgrade
!pip install opencv-python-headless==4.5.2.52

Step 4: Run the Notebook
Open the notebook cone_detection.ipynb from the Colab file explorer after cloning, and follow the instructions within to execute the project.
