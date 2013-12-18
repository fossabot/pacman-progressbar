Pacman-progressbar
==================

A ProgressBar for Python, based on Arch progressbar, with "ILoveCandy" option enabled.


Usage
=================

Import the package and create the bar
```python
from pacmanprogressbar import Pacman
 p = Pacman()
```

Parameters
----------
    start: It should be 0.
    end: Defines the bar's dimension in an amount of items or "steps", by default is 100.
    width: Size (in chars) of the bar, by default is the console size. 
    step: Current position in the progrressbar, Default 0.
    text: Write some text at the beginning of the line.
    

Methods
-------
``` python
p.update([value])
```
Update the progress, incresing the size by 1, or by the "value" parameter

```python
p.progress(value):
```
Set an specified progress, the parameters is mandatory:


Output
----------   
![Alt text](http://i.imgur.com/7oh3T6x.gif)
