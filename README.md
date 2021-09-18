# plotting-sine-wave-using-matplotlib
Here we are plotting a sine wave using matplotlib, Numpy and Pandas library of python
from matplotlib import pyplot as plt
import numpy as np
import pandas as pd
import math
%matplotlib inline
x=np.arange(0, math.pi*2, 0.05)
y=np.sine(x)
plt.plot(x,y)
plt.xlabel('angle')
plt.ylabel('sine')
plt.title('sine wave')
