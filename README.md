# JupyterLab
JupyterLab on Docker

# Reference

https://github.com/jupyterlab/jupyterlab

# Getting started

## Installation

```
git clone https://github.com/msakasai/JupyterLab.git
```

## Run Docker

```
# cd git clone directory
cd JupyterLab/

# cd docker direcroty
cd docker/

# build
docker-compose build

# up
docker-compose up
```

on console
```
  LabApp] The Jupyter Notebook is running at:
  LabApp] http://({container-id} or 127.0.0.1):8880/?token={token}
  LabApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
  LabApp] No web browser found: could not locate runnable browser.
  LabApp] 
     
     To access the notebook, open this file in a browser:
         file:///root/.local/share/jupyter/runtime/nbserver-1-open.html
     Or copy and paste one of these URLs:
         http://({container-id} or 127.0.0.1):8880/?token={token}
```

## Starting JupyterLab

#### access on browser
http://localhost:8880/lab?token={token}

![JupyterLab](https://github.com/msakasai/JupyterLab/blob/master/image/screen1.png?raw=true "JupyterLab1")

![JupyterLab](https://github.com/msakasai/JupyterLab/blob/master/image/screen2.png?raw=true "JupyterLab2")

