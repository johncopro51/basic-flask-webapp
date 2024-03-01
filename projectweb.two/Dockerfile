FROM python:3-alpine3.15
WORKDIR /PROJECTWEB.TWO
COPY . /PROJECTWEB.TWO/
RUN pip install -r requirements.txt
EXPOSE 5000
CMD ["python", "run.py", "--host=“0.0.0.0”"]