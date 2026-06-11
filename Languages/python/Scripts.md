Files that are read by your python interpreter.

Usually you run a script like, `python3 .\your_script_name.py`, `python .\your_script_name.py`, or `py .\your_script_name.py`.

# Reminder
Make sure to add a call guard!
```
# all the setup before the script does whatever it does

if "__main__" == __name__:
	# the script does what it does
```

# Examples
For example, make plots with [[plt]]
```
import math
import matplotlib.pyplot as plt

# colorblind palette
plt.style.use('seaborn-v0_8-colorblind')

# generating 65 points spanning from 0 to approximately 2π (~6.24)
num_points = 65
x_values = [0.1 * i for i in range(num_points)]
sin_values = [math.sin(x) for x in x_values]
cos_values = [math.cos(x) for x in x_values]

# initialize the figure and axis objects
fig, ax = plt.subplots(figsize=(9, 5))

# create scatter plots
ax.scatter(x_values, sin_values, label=r'$\sin(x)$', s=45, alpha=0.9, edgecolors='none') 
ax.scatter(x_values, cos_values, label=r'$\cos(x)$', s=45, alpha=0.9, edgecolors='none') 

# customize the axis properties (titles, labels, and grid) 
ax.set_title(r'Scatter Plot of $\sin(x)$ and $\cos(x)$ Functions', fontsize=14, fontweight='bold', pad=15) 
ax.set_xlabel('$x$ (radians)', fontsize=12) 
ax.set_ylabel('$y$', fontsize=12) 
ax.grid(True, linestyle='--', alpha=0.5) 
ax.legend(loc='upper right', frameon=True, facecolor='white', framealpha=0.9) 

if "__main__" == __name__:
	plt.show()
```