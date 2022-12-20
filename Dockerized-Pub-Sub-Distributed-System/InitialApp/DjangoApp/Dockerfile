FROM python:3.6.4-slim
COPY ./DemoApp /DemoApp
RUN pip install -r /DemoApp/requirements.txt
ENTRYPOINT ["python", "/DemoApp/manage.py"]
CMD ["runserver", "0.0.0.0:8000"]
EXPOSE 8000