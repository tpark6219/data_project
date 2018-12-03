FROM jupyter/datascience-notebook

RUN python --version

RUN conda install --quiet --yes -c \
    conda-forge osmnx dask                

VOLUME /notebooks
WORKDIR /notebooks
