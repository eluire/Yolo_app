# Yolo_app
A visual interface developed with python to support in object detection tests and output visualization. This application uses Yolo convolutional neural network as a base to detect objects.

## getting started
In this tutorial, we use Linux as OS, anaconda as environmental management and some packages like OpenCV, pyqt, and others. If you don't know some of these tools, check in the reference section to access the official documentation.

## steps to use
### 1. installing and setting Yolo CNN.
First you need clone the official repository containing a Yolo CNN, to this , run this command on your console:
```console
user@computer:~$ git clone https://github.com/AlexeyAB/darknet.git
```
Now click [here](https://pjreddie.com/darknet/yolo/) to visit the official site and setting your directory correctly, remember to check if your system configuration is available.

After this, move darknet  to inside the yolo_app directory:
```console
user@computer:~$ mv -r darknet yolo_app
```
### 2. create a new virtual environment.
we make available a file named *pyqt.yaml* no more than a complete setup with all needest packages to run this app.
run this command in your terminal:

```console
user@computer:~/yolo_app$ conda env create -f pyqt.yaml
```
if your env was created perfectly, execute this to enter inside of him:

```console
user@computer: conda activate pyqt
```
### 3. executing yolo_app interface.
