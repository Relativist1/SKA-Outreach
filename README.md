

<!--

*** 
*** 
*** 
-->
<!-- Intro -->
<br />
<p align="center">
  <img src="images/logo.png" alt="Logo" width="150" height="150">   
  
  <img src="images/vs.png" alt="Logo" width="130" height="130">
  <h3 align="center">SKA-Outreach-Pulsar-Hands-on-session</h3>
  <p align="center">
    Welcome to Pulsar Hands-on Session during SKA Outreach Week @ Vigyan Samagam.
  <p align="center">
    Here we will be doing data analysis using some pulsar data obtained before hand from various radio telescopes.
  </p>
</p>






# Downloads
Vela Pulsar Data (Download at least 1 file):
* https://drive.google.com/file/d/0B71z6CTGT4maU2JUY18yWFM2SU0/view?ts=58a78222
* https://drive.google.com/file/d/0B71z6CTGT4maVURwRk5BaUZJYmM/view?ts=58a78222
* https://drive.google.com/file/d/0B71z6CTGT4maQzc5RnJjd1FzNzQ/view?ts=58a78222
* https://drive.google.com/file/d/0B71z6CTGT4maQm90Y2NHcHRUNlU/view?ts=58a78222
* https://drive.google.com/file/d/0B71z6CTGT4maSG5XTndHbXVHTWM/view?ts=58a78222


Downloading the repository gives you the access to the contents available. Clone/Downlaod the repository using the top right button, save it to the desired folder and then unzip/unrar it.

# Using Python

## Installation [Method 1] (Recommended for Windows Users)

Python can be installed in many different ways with many distributions. For the hands-on sesion we will be using **Jupyter Notebook**. To get Jupyter notebook one can download Anaconda which is a python distribution software.
Anaconda for a specific operating system can be downloaded from https://www.anaconda.com/distribution/#download-section. Choose the appropriate operating system. Make sure to download **Python 3.7 version**.
Install using the installer.


## Installation [Method 2]

### Installing pip

#### Linux Users (Ubuntu)

Jupyter Notebook can be installed without installing Anaconda in your Linux system (Ubuntu). The following steps can be followed to install. If you have already installed pip, skip this step.

* Open the terminal and type the following command
```sh
$ sudo apt install python3-pip
```
* Now type the following command
```bash
$ pip install notebook
```
* Start Jupyter using
```bash
$ jupyter notebook
```
#### Mac Users

Mac users can go to this link https://bootstrap.pypa.io/get-pip.py and save the file as **get-pip.py**, then open the terminal and go to the folder where the downloaded file is and type the following command

```bash
$ python get-pip.py
````
* Now type the following command
```bash
$ pip install notebook
```
* Start Jupyter using
```bash
$ jupyter notebook
```
### Installing Python Libraries

Users who install python using the Method 2 need to install a few important python libraries as they are not installed via that method.
* numpy
* scipy
* matplotlib 
* pandas

* To install a library , open the terminal and type in the following command

```bash
$ pip install library_name
```
* Replace the library_name with the desired library and hit enter. For eg.

```bash
$ pip install matplotlib
```

## Using online

To use Jupyter Notebook online, go to https://jupyter.org/try and click on **Try Classic Notebook** and then a Jupyter Notebook will open.
