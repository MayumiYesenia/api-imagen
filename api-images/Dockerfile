FROM python:3-slim
WORKDIR /programas/api-images
RUN pip3 install flask
COPY . .
RUN python3 bd.py
CMD [ "python3", "./app.py" ]
