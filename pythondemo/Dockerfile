FROM python:2.7
LABEL maintainer="You Hao<yh_android@163.com>"
RUN pip install flask
COPY app.py /app/
WORKDIR /app
EXPOSE 5000
CMD ["python","app.py"]
