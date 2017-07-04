# gooey
Adds new features and widgets on top of Tkinter (Tk/Tcl for Python).

Gooey improves and modernises the apperances of regular Tkinter widgets, including the Button, Frame, and Entry widgets.
Dynamic update of borders and highlights around widgets on mouseover gives a responsive and intuitive feel to applications designed using this library.
Furthermore, new widgets include the Graph, Tooltip and Spacer, widening the capabilities of Tk for interface construction.

Gooey conforms to Tkinter syntax so closely that an existing Tkinter-dependant script can be changed to import gooey rather than Tkinter with no errors, resulting in aesthetic improvement.

The gooey script contains thorough commentary as well as a test script which is invoked when gooey.py is executed as the main program.

The gooey library is imported alongside Tkinter, for example: \n
  import gooey, Tkinter
Gooey widgets can then be instantiated similarly to Tkinter widgets: \n
  frame = gooey.Frame(parent)
