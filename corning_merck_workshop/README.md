# Merck - Corning Data Science Workshop
# Python & R Training

## Docker Setup
0. [Install Docker.](https://docs.docker.com/get-docker/)
0. [Additional setup for WSL 2 on Windows](https://docs.docker.com/docker-for-windows/wsl/)
1. ```$ cd path/to/corning_merck_workshop```
2. ```$ docker-compose up```
3. Navigate to Jupyter Lab at http://localhost:8888.
4. Open project notebooks in the `work` folder.

## Anaconda Setup
0. [Install Anaconda.](https://docs.anaconda.com/anaconda/install/index.html)
1. [Open Anaconda Navigator and launch JupyterLab.](https://docs.anaconda.com/anaconda/user-guide/getting-started/#run-python-in-a-jupyter-notebook)
1. Open a terminal from the launcher tab and run the following commands:
    * `$ conda install --yes -c conda-forge 'nodejs>=12.0.0'`
    * `$ jupyter labextension install jupyterlab-plotly`
    * `$ jupyter labextension install jupyterlab-dash`
2. Navigate to the project folder in the File sidebar tab. Double-click on a notebook to launch.