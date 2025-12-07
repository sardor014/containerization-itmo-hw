FROM jupyterhub/jupyterhub:latest

RUN apt-get update
RUN apt-get install -y vim
RUN apt-get install -y git
RUN apt-get install -y nano

WORKDIR jupyter_folder
VOLUME /jupyter

ENTRYPOINT ["jupyterhub", "--log-level=DEBUG"]