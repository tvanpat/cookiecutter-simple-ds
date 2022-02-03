FROM jupyter/scipy-notebook

COPY ./docker_requirements.txt ./
RUN pip install -r docker_requirements.txt

COPY docker_config/overrides.json /opt/conda/share/jupyter/lab/settings/

RUN jupyter serverextension enable --py jupyterlab --sys-prefix
RUN jupyter labextension enable @jupyterlab/plotly-extension
RUN jupyter lab build