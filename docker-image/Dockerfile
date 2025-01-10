FROM quay.io/jupyter/all-spark-notebook:spark-3.5.3

ADD requirements.txt .

RUN pip install -r requirements.txt

WORKDIR /home/jovyan/work
