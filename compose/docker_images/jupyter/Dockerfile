FROM quay.io/jupyter/base-notebook:latest

WORKDIR /home/jovyan/work

COPY ./compose/docker_images/jupyter/assets/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt
