FROM python:3.8-slim
WORKDIR /KuberByBTA
COPY . /KuberByBTA
RUN pip install Flask pymongo
EXPOSE 5000
CMD ["python", "app.py"]

