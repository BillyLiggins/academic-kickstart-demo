+++
title = "Jupyter notebook"
date = "2019-04-12T23:16:44+01:00"
draft = false
# disable_comments = false
comments = false

+++

# Title

The imports:
```python
import matplotlib.pyplot as plt
%matplotlib inline
```

The simplest plot possible.
```python
fig,ax= plt.subplots()
ax.plot(range(9),range(9))
fig.show()
```
![alt text](output_1_1.png,"yeah")
