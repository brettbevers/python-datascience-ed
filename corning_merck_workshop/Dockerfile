FROM jupyter/datascience-notebook:python-3.9.4

USER $NB_USER

RUN jupyter labextension install jupyterlab-plotly jupyterlab-dash

RUN conda install --quiet --yes \
    'jupyter-dash'