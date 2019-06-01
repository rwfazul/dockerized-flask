FROM python:3.6
LABEL maintainer 'Rhau <rwfazul at inf.ufsm.br>'

ENV PYTHONUNBUFFERED 1

COPY . /opt/app
WORKDIR /opt/app
RUN pip install -r requirements.txt
EXPOSE 3000

ENTRYPOINT ["/usr/local/bin/python"]
CMD ["app.py"]
