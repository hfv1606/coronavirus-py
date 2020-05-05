FROM python

WORKDIR /code

COPY requirements.txt app.py ./

RUN pip install -r requirements.txt

EXPOSE 8050

CMD ["python", "app.py"]
