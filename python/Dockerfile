FROM python:alpine
RUN pip install redis
RUN pip install requests
COPY script.py /
CMD ["python", "script.py"]