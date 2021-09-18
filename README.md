# plotting-sine-wave-using-matplotlib
<br> Here we are plotting a sine wave using matplotlib, Numpy and Pandas library of python </br>
<br> from matplotlib import pyplot as plt </br>
import numpy as np
<br> import pandas as pd </br>
import math
<br> %matplotlib inline </br>**Inline function ensures that the graph is displayed inside the jupyter notebook**
<!--- the inline keyword ensures that your graph gets displayed inside your jupyter notebook --->
x=np.arange(0, math.pi*2, 0.05)
<br> y=np.sine(x) </br>
plt.plot(x,y)
<br> plt.xlabel('angle') </br>
plt.ylabel('sine')
<br> plt.title('sine wave') </br>

