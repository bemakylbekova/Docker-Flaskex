FROM python
LABEL maintainer="bemaangel49@gmail.com"
COPY Flaskex/ /app/
WORKDIR /app/
RUN pip install -r requirements.txt
EXPOSE 5000
CMD ["python", "app.py"]
