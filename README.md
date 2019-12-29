# LiBSizing-Desktop-Tool-Public Installer
____
### LiB Sizing Model Info

This is the Python implementation of the *LiB Sizing Excel Workbook* version *v1_2*. The source code is in a private repository.



<h3>Downloads</h3>

To download the application you must be authorized. Ask for permissions from the author to be granted download privileges.




**v_1.0**
* [Download Installer Windows](https://drive.google.com/file/d/1QuvIPV27RiGDs_m5ZYZoJKNYXmLh26NM/view?usp=sharing)

# LiBSizing-Desktop-Tool Source Code
___
Source Code : [Code](https://github.com/diegotorres1/LiBSizing-Desktop-Tool)
* This is a private repository *


## Installation
### Preface
LiBSizingModel Desktop Tool runs on Python 3.6 > . There are multiple options for the installation of Python. It is recommended to create a virtual environment for the dependencies that you will be installing. 
### Step 1 
Git clone the repository and change (cd) to the working directory to the cloned folder.
```shell
git clone https://github.com/diegotorres1/LiBSizing-Desktop-Tool.git
cd LiBSizing-Desktop-Tool
```
### Step 2
In this example I will be using Anaconda, a simple package management system, to create an environment to work in. Enviroments are used to isolate libraries and other resources used within a project, from other projects that you develop that choose to use different libraries and resources.
* Install [Anaconda](https://www.anaconda.com/distribution/#windows). Download the latest Python Version number.
* Open the Anaconda Prompt. All further *Steps* will be ran in the prompt.
* Create a new environment and activate it.
```shell
conda create --name libsizingtool python=3.6.9
activate libsizingtool
```

### Step 3
The requirements.txt file contains the list of dependencies to install. PIP, a package management tool equipped in Anaconda, has an option to auto install all files listed in the requirements.txt file. Run 
```shell
  pip install -r requirements.txt
```
### Step 4
The application now has access to all of the dependencies. Run the application by running the main.py.
```code
  python main.py
```


## Downloadable Versions 
*The downloadable versions contain stable, yet incomplete versions of the tool. It is recommended that you clone the repository.*
### Current Version
[1.01]("https://drive.google.com/file/d/1NYo_DqvScYdLnHOCMLmxzt9Fdit6XFaQ/view?usp=sharing")
### Previous Version


### How to Use

### How the Code Works (Overview)
Docs :  [LiBSizing Desktop App Code Documentation](https://docs.google.com/document/d/1cyXd1JR5woGf3R2D_Wbo2L6VVybvxdE-Te5lBYCdhuE/edit?usp=sharing)
