FROM python:2.7

RUN pip install kafka-python
RUN pip install --pre cassandra-driver
RUN pip install --pre --upgrade cassandra-driver
RUN pip install cqlengine

ADD rsvp_consumer.py /
ADD util.py /
ADD database.py /

CMD [ "python", "./rsvp_consumer.py" ]
