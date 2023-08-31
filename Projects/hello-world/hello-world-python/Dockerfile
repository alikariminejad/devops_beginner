FROM python:alpine3.10
WORKDIR /app
COPY . /app
RUN pip install -r requiremnts.txt
EXPOSE 5000
CMD python ./launch.py

#COPY requiremnts.txt /app/requirements.txt
#ENTRYPOINT ["python", "./launch.py"]