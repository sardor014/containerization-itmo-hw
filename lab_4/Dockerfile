FROM jupyterhub/jupyterhub:3.1.1

WORKDIR /jupyter

RUN pip install notebook jupyterlab

VOLUME /jupyter

ENTRYPOINT ["jupyterhub", "--log-level=DEBUG"]