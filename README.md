# Yolo_app

![img](./icons/demonstration_img.png)

A visual interface developed with python to support object detection tests and output visualization. This application uses the YOLO convolutional neural network as a base object detector.

## Getting started

In this tutorial, we use the Linux OS, Anaconda as an environment manager and some modulos like OpenCV, pyqt, and others. If you don't know some of these tools, check in the reference section to access the official documentation.

### Installing and configure Yolo CNN.

First, you need to configure your system to run YOLO CNN, to this, visit
the following repository. [Click here](https://github.com/vanluwin/enviroment)
https://github.com/vanluwin/enviroment)

After this, you are able to execute the YOLO CNN, in this repository, we provide a folder called darknet, open it and run the following command in your terminal

```console
user@computer:~$ make
```
Now if you want to know more about how the YOLO Convolutional neural network works, visit these sites.[Official repository](https://pjreddie.com/darknet/yolo/) [Official site](https://github.com/AlexeyAB/darknet#how-to-train-to-detect-your-custom-objects)

### Weigths

We make available to you a specific weight file to vehicles detection, if you want to download this file click on the following link.[Click here](link_pro_download)

If you want to know how we create this weight file, see all of the statistics and detection metrics and more about our job with image processor and object detection, check the following link.[Click here](link para artigo)

But if you have your own file of weights just move to the darknet folder.

### Create a new virtual environment.

We make available a file named *pyqt.yaml*, which is no more than a complete setup with all needed packages to run this app.

Run the following command in your console:

```console
user@computer:~/yolo_app$ conda env create -f pyqt.yaml
```

If your environment was created correctly, execute this to enter activate it:

```console
user@computer:~/yolo_app$ conda activate pyqt
```

So now let's get started with Yolo app!

## Steps to use

### Executing the yolo_app interface.

Inside of your virtual environment run the following command:

```console
user@computer:~/yolo_app$ python yolo.py
```
if all of the things are correct, you will see this screen.

![img](./icons/screen.png)
