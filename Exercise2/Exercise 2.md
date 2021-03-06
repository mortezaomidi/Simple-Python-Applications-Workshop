# Exercise 2: Keeping it Classy
#### In this exercise we will learn the Python class structure and use it with our application

## Example Class:
The example below is an empty class with the structure in place to create the same app as we did in Exercise 1.
Your task is to take the code from Exercise 1 and slot it into the appropriate places in our new class App. If you need some hints reference the finished example for this exercise.
```python
from Tkinter import *

class App():

  # Create class-level attribute Tk instance

  def __init__(self):

    # Execute core methods
    pass

  def config_widgets(self):

    # Insert widgets
    pass

  def run_app(self):

    # Enter the Tkinter event loop
    pass

if __name__ == '__main__':
    new_window = App()
```

## General Workflow:

The general workflow remains the same:

1. Import **all** from Tkinter.
2. Define the class name as **App**.
3. Create Tk **root** window widget as a class-level attribute.
4. In the **init** method, we run the core methods
    - Configure app
    - Configure widgets
    - Run app

#### Running the code again, it should create the same app, now just a bit more classy behind the scenes.
