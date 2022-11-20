FROM thespaghettidetective/web:base-1.8

WORKDIR /app
EXPOSE 3334

ADD /backend /app
ADD /frontend /frontend

RUN pip install -U pip
RUN pip install -r requirements.txt
