FROM python:2.7

RUN pip install kafka-python
RUN pip install websocket-client

ADD rsvp_producer.py /

CMD [ "python", "./rsvp_producer.py" ]