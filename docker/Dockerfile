FROM python:3

RUN apt-get -y update && apt-get -y upgrade

RUN pip install --upgrade pip
RUN echo $(pip -V)

RUN pip install --upgrade setuptools
RUN pip install jupyterlab

# RUN
CMD ["jupyter", "lab", "--ip=0.0.0.0", "--port=8880", "--allow-root"]
