# PyOpenGl Window Structure
> - By **Muhammad Umar Anzar**
> - Seat No. **B19102104**
> - University Of Karachi 
> - UBIT department of computer science
> - Subject Computer Graphics

## Description
Window Structure of PyQt5 to run PyOpenGL for educational purposes.

## Dependencies
- PyQt5
- PyOpenGL
- freeglut.dll

**To install these libraries Follow the steps mentioned below:**

> On the command prompt, type this to install **PyQt5**
```
pip install PyQt5
```

To install **PyOpenGL** you need to be careful of the python `version` you are using and your system architecture i.e `32` or `64` because PyOpengGL version should match the version of python you are using.

>First download PyOpenGL and PyOpenGL_accelerate wheel files that are available in the link mentioned below:

>Link to download PyOpenGL: https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyopengl

For Example, if you are using **python version 3.7** then you need to download these files
- PyOpenGL_accelerate‑3.1.6‑cp37‑cp37m‑win_amd64.whl
- PyOpenGL‑3.1.6‑cp37‑cp37m‑win_amd64.whl

Where cp37 is the identification of py version 3.7.
Similarly, cp39 is the identifying py version 3.9.

>After that put both of these wheel files (.whl) in a new folder and open the location of the new folder in the command prompt and run these commands :

```
pip install PyOpenGL-3.1.3b2-cp37-cp37m-win_amd64.whl
pip install PyOpenGL_accelerate-3.1.3b2-cp37-cp37m-win_amd64.whl
```
Again be careful of the version of python and PyOpenGL you are using and install the packages with the correct name of your PyOpenGl version.

>Lastly, you need to place `freeglut.dll` in your Windows folder, usually, it is located in `C drive` i.e, 
```
C:\Windows
```

