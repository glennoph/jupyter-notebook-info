# 00-install
## Install options
* python3

`pip install jupyter pandas numpy scipy matplotlib`

* anaconda

* docker

`docker run -it --rm -p 8888:8888 -v ~/src/jupyter-course:/home/jovyan jupyter/datascience-notebook`

## Setup
* checkout the existing notebooks and start jupyter notebook (on t3600)
```
cd ~/src/github.com/PacktPublishing
jupyter notebook
```

## New Notebook
* Select Python 3
* Change Name of notebook
* Enter python code in cell then Shift/Enter to run

### Imports
```python
import numpy as np
import pandas as pd
```
### Sample commands
```python
arr1 = np.random.rand(10)
arr1
```

```python
ser1 = pd.Series(arr1)
ser1
```


