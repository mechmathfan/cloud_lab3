FROM python:2.7
WORKDIR /app
COPY notejam /app/
COPY requirements.txt /app/
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]


