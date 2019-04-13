+++
title = "Jupyter notebook"
date = "2019-04-12T23:16:44+01:00"
draft = false
# disable_comments = false
comments = false

+++

# Title

```python
import matplotlib.pyplot as plt
%matplotlib inline
```

    
    Bad key "ytick.fontweight" on line 9 in
    /home/billy/.config/matplotlib/stylelib/snoplus.mplstyle.
    You probably need to get an updated matplotlibrc file from
    http://github.com/matplotlib/matplotlib/blob/master/matplotlibrc.template
    or from the matplotlib source distribution
    
    Bad key "xtick.fontweight" on line 10 in
    /home/billy/.config/matplotlib/stylelib/snoplus.mplstyle.
    You probably need to get an updated matplotlibrc file from
    http://github.com/matplotlib/matplotlib/blob/master/matplotlibrc.template
    or from the matplotlib source distribution



```python
fig,ax= plt.subplots()
ax.plot(range(9),range(9))
fig.show()
```

    /home/billy/.local/lib/python2.7/site-packages/matplotlib/figure.py:403: UserWarning: matplotlib is currently using a non-GUI backend, so cannot show the figure
      "matplotlib is currently using a non-GUI backend, "


![png](static/img/output_1_1.png)
