import numpy as np
import matplotlib.pyplot as plt

np.random.seed(42)

# Draw sample from a distribution  
loc, scale = 2, 0.1
samples = np.random.gumbel(loc, scale, 1000)    

# Perform the transformation on the samples here ...
count, bins, ignored = plt.hist(samples, 100, density = True)
plt.show()
