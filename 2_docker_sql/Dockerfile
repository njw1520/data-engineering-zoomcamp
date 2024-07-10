FROM python:3.9

RUN pip install pandas:1.3.4 jupyterlab 

WORKDIR /app
COPY pipeline.py pipeline.py

ENTRYPOINT [ "python", "pipeline.py" ]
