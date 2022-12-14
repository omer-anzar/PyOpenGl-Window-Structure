# PyOpenGl Window Structure
> - By **Muhammad Umar Anzar**
> - Seat No. **B19102104**
> - University Of Karachi 
> - UBIT department of computer science
> - Subject Computer Graphics

## Description
GUI Window Structure of PyQt5 to run PyOpenGL for educational purposes.

## Dependencies
- PyQt5
- PyOpenGL
- freeglut.dll

## Installation of Libraries
**To install these libraries Follow the steps mentioned below:**
### Step 1
On the command prompt, type this to install **PyQt5**
```
pip install PyQt5
```

### Step 2
To install **PyOpenGL** you need to be careful of the python `version` you are using and your system architecture i.e `32` or `64` because the PyOpengGL version should match the version of python you are using.

First download PyOpenGL and PyOpenGL_accelerate wheel files that are available in the link mentioned below:

- Link to download PyOpenGL: https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyopengl

For Example, if you are using **python version 3.7** then you need to download these files
- PyOpenGL_accelerate‑3.1.6‑cp37‑cp37m‑win_amd64.whl
- PyOpenGL‑3.1.6‑cp37‑cp37m‑win_amd64.whl

Where cp37 is the identification of py version 3.7.

Similarly, cp39 is identifying the py version 3.9.
If you have a 32-bit Operating system then download win_32 files.

### Step 3
After that put both of these wheel files (.whl) in a new folder and open the location of the new folder in the command prompt and run these commands:

```
pip install PyOpenGL-3.1.3b2-cp37-cp37m-win_amd64.whl
pip install PyOpenGL_accelerate-3.1.3b2-cp37-cp37m-win_amd64.whl
```
Again be careful of the version of python and PyOpenGL you are using and install the packages with the correct name of your PyOpenGl version.

That's All Folks.
<hr>

### Step 4 (If the above steps don't work )
If the above steps don't work, then just install python 3.7 and download all of the PyOpenGL packages from my repository `Packages folder` including freeglut.dll and do the steps from 1 to 3.
Lastly, place the `freeglut.dll` file in your Windows folder. Usually, it is located in the `C drive` i.e, 
```
C:\Windows
```
NOTE:- Download the PyOpenGL win32 `.whl` file if you're using the 32-bit operating system.

## How to Run and Edit
In `Python Code Folder`, there are two files, `PyQtWindow` is considered the GUI Window but this file is not the main file.

The other file, `GL_window` is considered the **main file** which runs and opens the program.

`GL_window` includes a class `GLWidget` that is inheriting the PyQt OpenGL widget and whatever You want to draw and animate, you need to write implementation in the `paintGL` function of the `GLWidget` class.

Background Color and other initialization functions of OpenGL can be edited and added in the `initializeGL` function of the `GLWidget` class.

NOTE:- YOU NEED TO EXECUTE `GL_window.py` TO RUN YOUR PROGRAM.

## QTimer To Update GL widget
I have to use the Qtimer of PyQt to animate the widget. In other words, updating the widget by a delay timer. 
