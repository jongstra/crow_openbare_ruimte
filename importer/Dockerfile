FROM amsterdam/python

RUN rm -rf /data
RUN mkdir /data

COPY requirements.txt /app/

RUN pip install -r requirements.txt

COPY . /app/

