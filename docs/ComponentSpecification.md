# Component Specification

## Software components.

Core Dependencies
- For calculations: numpy
- For animation: matplotlib.pyplot 
- To create a GUI: tkinter 
- To manage file structure: import os

Components:
- display GUI
   - Requires default values
   - outputs starting animation values
- display animation
   - Requires animation values across a time series
- calculate animation values
   - Requires starting animation values
   - outputs animation values across a time series

# Interactions
The information flows from the GUI to the calculations to the animation. 

# Preliminary plan. A list of tasks in priority order.
<ol>
<li> calculate animation values </li>
<li> display animation </li>
<li> edit calculation values</li>
<li> display GUI </li>
<li> have GUI inputs edit calculation values</li>
</ol>
