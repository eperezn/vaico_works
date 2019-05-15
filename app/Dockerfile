FROM python

ARG PORT=5000
ENV PORT $PORT

ADD . /code
WORKDIR /code
RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "app_api.py"]
