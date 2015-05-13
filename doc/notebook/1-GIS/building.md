```python
>>> import pylayers.gis.ezone as ez
>>> import matplotlib.pyplot as plt
>>> import numpy as np
>>> import os
>>> %matplotlib inline
```

```python
>>> prefix=ez.enctile(-1.5,47.5)
>>> print prefix
N47W002
```

```python
>>> E=ez.Ezone(prefix)
```

```python
>>> E
N47W002
--------
(-2, -1, 47, 48)
latlon : [ -0.000 75118.790 cartesian :0.000 111194.505 ]
```

```python
>>> E.getdem()
Load srtm file
no aster file for this point
```

```python
>>> E.show(clim=[-20,180])
(<matplotlib.figure.Figure at 0x7ffa46a9de50>,
 <matplotlib.axes.AxesSubplot at 0x7ffa46ab62d0>)
```

```python
>>> E
N47W002
--------
(-2, -1, 47, 48)
latlon : [ -0.000 75118.790 cartesian :0.000 111194.505 ]
```

```python

```