# Simple 2D L-System Python Implmentation

<img width="1920" alt="1" src="./assets/demo_img.png">

## About:
- I always wanted to implment an L-System, so I did.
- To learn more about L-Systems [HERE](https://en.wikipedia.org/wiki/L-system)
- Originally this project was a terminal only program, but though tkinter, it evolved to a GUI & terminal program.
- This project use to be in the algorithm-challenges repo, which has been deprecated until further notice. Due to this, I moved this project to this new repo.

## Content:
- This project consists of the following files:
	- draw.py : class with function which does all the L-System drawing using turtle.
	- pfuncs.py : class with functions used to save/load pickle files with L-System saves. It also contains functions for getting the current pwd and creating a list of every file path to a pickle file in the project folder.
	- main.py : main python script for this project. Here the GUI is setup and ran as well as everything else. The main.py script depends on draw.py and puncs.py.
- For this project, there are two other directories:
	- tools : contains useful scripts as well as some random files and some backup files
	- saves : contains all the L-System saves I saved so far
- In tools/, there is a python script called eps_to_png.py. This is a script that can convert an inputed .eps file to a .png file.
	- This script works most of the time, but fails sometimes. So I did not want to include it in the final code.

## Tested On:
- Operating Systems:
	- MacOS Catalina (10.15.7)
	- Ubuntu 20.04
- Software:
	- Python3 3.8.13

## Requriements:
- Python3
	- Built-In Pkgs:
		- tkinter
		- turtle
		- subprocess
		- os

## How To Use:
- Run main.py script to run everything, with the following command (run this once and after you understand the warning message, then start running this command with the -nw option):
	```
	python3 main.py
	```
- Run the main.py script without the initial warning message everytime:
	```
	python3 main.py -nw
	```
- To convert an eps file to a png, you can use the eps_to_png.py python script by running a command like this:

	```
	python3 eps_to_png.py example.eps example.png
	```

## Future Plans:
- This code is not perfect and is limited to 2D only. So in the feature I would like to implment this code for 3D L-Systems. I might need to use either Pygame or Unity, I will most liky use Unity for a 3D implmentation of this.

## Great Sources I Used:
1. https://en.wikipedia.org/wiki/L-system
2. http://paulbourke.net/fractals/lsys/
3. http://www.motionesque.com/beautyoffractals/
4. http://paulbourke.net/fractals/lsys/
5. https://www.python-course.eu/tkinter_entry_widgets.php
6. https://www.python-course.eu/tkinter_text_widget.php
7. https://www.geeksforgeeks.org/open-a-new-window-with-a-button-in-python-tkinter/
