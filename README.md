## Overview

Jupyter notebooks to help with learning python.

## Setup

### Python

On a Mac or Linux system the Python executable should already be installed.  Also `pip` should be present.
For the rest of these instructions we need to create a Python virtual environment so that Jupyter can be installed locally.

If the `virtualenv` command isn't installed then run the following as administrator

```
pip install virtualenv
``` 

You should then be able to create the virtual environment

```
virtualenv localpy
```

and activate it

```
. ./localpy/bin/activate
```

### Jupyter

Having got the virtual environent setup you can now install Jupyter

```
pip install jupyter
```


## Using Jupyter

### Startup

Run the following command to start the Jupyter webserver

```
jupyter notebook
```

This will start the server and open a browser window at the [tree view](http://localhost:8888/tree)

You can now navigate to any of the `*.ipynb` files and open these to view/run the code inside.

There is also a button (top right) for creating a new file.





