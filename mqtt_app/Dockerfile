FROM python:3.6

WORKDIR /app

COPY ./ /app

RUN pip3 install --upgrade pip
RUN pip3 install -r requirements.txt

CMD python3 ws.py
