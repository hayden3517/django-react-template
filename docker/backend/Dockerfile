# docker/backend/Dockerfile

FROM continuumio/miniconda3:latest 

WORKDIR /app
ADD ./backend/environments.yml /app/backend/

RUN conda env update --name base --file backend/environments.yml

ADD ./docker /app/docker
ADD ./backend /app/backend