FROM jupyter/datascience-notebook

# RUN conda install --quiet --yes \
#   'pydot' \
#   'tensorflow=1.13*' \
#   'keras=2.2*' && \
#   conda clean --all -f -y && \
#   fix-permissions $CONDA_DIR && \
#   fix-permissions /home/$NB_USER

RUN pip --no-cache-dir install tensorflowjs==0.1.1
# USER root
# RUN apt-get update && \
#   apt-get -y install graphviz && \
#   rm -rf /var/lib/apt/lists/*